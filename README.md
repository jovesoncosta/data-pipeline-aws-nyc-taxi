# 🚀 Projeto de Pipeline de Dados: Análise de Corridas de Táxi de NYC Jan/2024

## 🎯 Objetivo
Este projeto implementa um pipeline de dados completo e automatizado que extrai, transforma e carrega (ETL) dados de corridas de táxi de Nova York. Os dados são modelados em um esquema estrela (Star Schema) e disponibilizados para análise em um dashboard.

## 🏛️ Arquitetura da Solução
Esta arquitetura de Data Lakehouse na nuvem demonstra um fluxo de dados moderno, escalável e custo-eficiente, desde a extração dos dados brutos até a visualização final.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python 3 (Pandas, AWS Wrangler)
- **Cloud (AWS):** S3 (Data Lake), Glue (Data Catalog), Athena (Query Engine)
- **Visualização:** Microsoft Power BI
- **Controle de Versão:** Git & GitHub

## ✨ Modelagem de Dados
Os dados foram estruturados em um Modelo Estrela (Star Schema) para otimizar as consultas e a performance do dashboard. A `fato_corridas` fica no centro, conectada a múltiplas dimensões que fornecem o contexto analítico.

## 📊 Dashboard Final
O dashboard no Power BI consolida os dados e permite a exploração dos principais KPIs.

*Visão Geral do Dashboard:*
*Análise Detalhada (Exemplo com Filtro Aplicado):*
## ⚙️ Como Executar o Projeto
1.  Clone este repositório.
2.  Instale as dependências: `pip install pandas awswrangler jupyter`
3.  Configure suas credenciais da AWS no notebook.
4.  Execute as células do notebook `pipeline_aws.ipynb`.
5.  Configure o Crawler no AWS Glue e conecte o Power BI ao Athena (via Driver ODBC).

<img width="1632" height="560" alt="BUCKET S3" src="https://github.com/user-attachments/assets/1b039f69-6d49-48e3-abc0-b4ca87bdb4fb" />

<img width="1637" height="658" alt="GLUE TELA TABELAS" src="https://github.com/user-attachments/assets/2cbc2723-a2e1-46ea-b54e-3335d0295f18" />

<img width="1898" height="837" alt="CONSULTA ATHENAS" src="https://github.com/user-attachments/assets/512119a7-8dad-4f82-87fb-dc67c6ebc794" />

<img width="1430" height="805" alt="DASH_TEMPORARIO" src="https://github.com/user-attachments/assets/dabebd3c-86a7-4dfe-875e-60423bc5ba9d" />
