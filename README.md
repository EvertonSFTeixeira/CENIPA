# CENIPA

# Análise de Dados de Ocorrências Aeronáuticas (CENIPA)

Este repositório contém uma análise exploratória dos dados de ocorrências aeronáuticas fornecidos pelo Centro de Investigação e Prevenção de Acidentes Aeronáuticos (CENIPA). O objetivo deste projeto é entender o comportamento dos acidentes e incidentes aeronáuticos no Brasil, identificando padrões e insights relevantes para aumentar a segurança na aviação.

## Conteúdo

- [Contexto](#contexto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Análise Realizada](#análise-realizada)
- [Como Executar](#como-executar)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Contexto

Os dados de ocorrências aeronáuticas no Brasil foram disponibilizados pelo CENIPA e contêm informações sobre diversos aspectos das ocorrências, como a fase de voo, o tipo de aeronave, o número de vítimas e o ano de ocorrência. Este projeto visa analisar esses dados para obter insights sobre os fatores que contribuem para incidentes e acidentes na aviação.

## Tecnologias Utilizadas

- **Python**: Linguagem principal utilizada para a análise e manipulação de dados.
- **Jupyter Notebook**: Ferramenta utilizada para visualização de dados e execução do código.
- **Bibliotecas**:
  - `Pandas` - Manipulação e análise de dados
  - `os` - Manipulação de diretórios e arquivos do sistema operacional

## Estrutura do Projeto

```plaintext
.
├── Analise.ipynb            # Notebook principal com a análise de dados
├── README.md                # Descrição do projeto
├── data/                    # Diretório para os dados brutos
```

## Análise Realizada

A análise abrange os seguintes aspectos:

1. **Distribuição Temporal de Ocorrências**: Análise do número de ocorrências ao longo dos anos.
2. **Classificação de Ocorrências**: Exame das categorias de ocorrências mais comuns, como incidentes graves, acidentes e outros tipos.
3. **Fase do Voo e Causas Primárias**: Identificação das fases de voo em que ocorrem mais incidentes e análise das causas principais.
4. **Distribuição Geográfica**: Visualização dos estados com maior número de ocorrências.
5. **Outros Fatores Contribuintes**: Investigação de outros fatores, como tipo de aeronave e condição meteorológica no momento da ocorrência.

## Como Executar

Para executar a análise localmente:

1. Clone o repositório:
   ```bash
   git clone https://github.com/EvertonSFTeixeira/CENIPA.git
   ```

2. Instale as dependências:
   ```bash
   pip install pandas os
   ```

3. Abra o notebook `Analise.ipynb`:
   ```bash
   jupyter notebook Analise.ipynb
   ```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias, correções ou novas funcionalidades.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
