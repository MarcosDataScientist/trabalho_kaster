# Trabalho Prático: Data Warehouse Relacional e ETL em SQL

## Alunos
- Marcos Vinicius
- Lucas Silva

## Resumo do Projeto
O tema central escolhido para este projeto é a análise de **acidentes de trânsito**. A proposta do trabalho é montar um **data warehouse relacional**, integrando diferentes fontes de dados relacionadas ao tema e com a etapa de ETL (Extração, Transformação e Carga) primariamente implementada em SQL, para a execução de consultas analíticas.

**Objetivo:** Adquirir conhecimentos práticos do processo de integração de dados em um ambiente analítico primariamente utilizando recursos de SQL.

## Fontes de Dados
Os conjuntos de dados utilizados contemplam os formatos XML, JSON e tabular:

- **Dados em XML:** [IBGE - Agregados](https://servicodados.ibge.gov.br/api/docs/agregados?versao=3)
- **Dados em JSON:** [Brasil API](https://brasilapi.com.br/docs)
- **Dados Tabulares:** *(A definir)*

## Tecnologias e Ferramentas
- **Linguagem:** Python 3.11 (Recomendado devido à excelente estabilidade, velocidade e amplo suporte a bibliotecas de dados e SGBDs).
- **Banco de Dados Relacional:** PostgreSQL
- **Conexão com Banco de Dados:** `psycopg` (A versão moderna do psycopg2, altamente otimizada para integração entre Python e PostgreSQL).

## Etapas de Desenvolvimento
1. **Modelagem:** Implementação de um esquema relacional de banco de dados analítico (estrela, floco de neve ou constelação de estrelas) para o armazenamento integrado.
2. **Staging:** Carga dos conjuntos de dados originais em tabelas temporárias.
3. **ETL em SQL:** Processamentos necessários utilizando SQL (incluindo as extensões SQL/XML e SQL/JSON) para transportar e transformar os dados das tabelas temporárias para as tabelas do esquema analítico.
4. **Consultas e Análises:** Implementação de consultas SQL para gerar análises relevantes sobre os dados, explorando diferentes recursos como:
   - Agregações simples
   - Uso de `CASE` e tratamento de nulos
   - Operações OLAP
   - Funções de janela (Window Functions)
   - Views / Materialized Views

## Entrega
**Data da apresentação:** 25/05/2026
