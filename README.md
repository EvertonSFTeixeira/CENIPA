<div align="center">
    <img src="https://github.com/user-attachments/assets/ff767008-70ed-428b-b349-d186fc1083a6" alt="CENIPA" width="400"/>
</div>

# Análise de Dados de Ocorrências Aeronáuticas (CENIPA)

## Descrição do Projeto
Este projeto realiza uma análise exploratória de dados de ocorrências aeronáuticas no Brasil, utilizando dados fornecidos pelo Centro de Investigação e Prevenção de Acidentes Aeronáuticos (CENIPA). O objetivo é identificar padrões e insights que contribuam para uma maior compreensão dos acidentes e incidentes, auxiliando na implementação de estratégias de segurança mais eficazes na aviação. O processo inclui uma etapa de ETL (Extração, Transformação e Carregamento), na qual os dados brutos são extraídos de diferentes fontes, transformados para garantir consistência, qualidade e usabilidade, e carregados em uma estrutura adequada para análise. Essa etapa é essencial para estruturar os dados de forma eficiente, permitindo insights mais precisos e análises aprofundadas sobre os fatores que influenciam a segurança na aviação.

## Conjunto de Dados
Os dados utilizados no projeto estão disponíveis publicamente e incluem informações detalhadas sobre diversas ocorrências aeronáuticas. Cada registro abrange aspectos como fase de voo, tipo de aeronave, número de vítimas, causas e localidade do incidente.

- **Fonte dos dados**: CENIPA (Centro de Investigação e Prevenção de Acidentes Aeronáuticos)
- **Colunas**: O conjunto de dados inclui várias colunas representando variáveis como a categoria do evento, localização, tipo de aeronave e outros fatores contextuais.
- **Arquivos**:
  - `ocorrencias.csv`: Dados completos das ocorrências aeronáuticas.
  - `aeronave.csv`: Dados completos sobre as aeronaves.

## Estrutura do Projeto
```
├── Analise.ipynb            # Notebook principal com a análise de dados
├── README.md                # Descrição do projeto
└── data/                    # Diretório para os dados brutos
```

## Objetivo
O objetivo deste projeto é explorar e analisar dados de ocorrências aeronáuticas para identificar padrões, tendências e variáveis importantes, contribuindo para uma compreensão mais detalhada dos fatores envolvidos nos acidentes e incidentes aéreos.

## Análise Realizada
A análise abrange os seguintes aspectos:

1. **Distribuição Temporal de Ocorrências**: Análise da frequência de ocorrências ao longo dos anos.
2. **Classificação de Ocorrências**: Identificação das categorias de ocorrências mais comuns, como incidentes graves e acidentes.
3. **Fase do Voo e Causas Primárias**: Análise das fases de voo com maior frequência de ocorrências e das causas principais.
4. **Distribuição Geográfica**: Visualização dos estados com maior número de ocorrências.
5. **Outros Fatores Contribuintes**: Análise de variáveis adicionais, como tipo de aeronave e condições meteorológicas.

## Resultados
A análise identificou tendências e padrões importantes, como as fases de voo mais suscetíveis a incidentes, regiões com maior número de ocorrências e os tipos de aeronaves envolvidos. Esses insights são essenciais para melhorar as estratégias de prevenção e aumentar a segurança aeronáutica.

## Instalação

### Requisitos
Para rodar este projeto, você precisará dos seguintes pacotes instalados:

- `Pandas`
- `OS`

Para instalar as dependências, você pode usar o arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

### Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/EvertonSFTeixeira/CENIPA.git
   ```

2. Abra o notebook `Analise.ipynb`:
   ```bash
   jupyter notebook Analise.ipynb
   ```

## Conclusão
Este projeto demonstrou a aplicabilidade de métodos de análise de dados na compreensão das ocorrências aeronáuticas. A análise dos dados de incidentes e acidentes permitiu identificar padrões e fornecer insights valiosos para a segurança aérea.
