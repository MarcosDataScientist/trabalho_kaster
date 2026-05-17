RESUMO: A proposta de trabalho é montar um data warehouse relacional, integrando diferentes fontes de dados e com ETL primariamente implementada em SQL, para execução de consultas sobre esses dados.

OBJETIVO: adquirir conhecimentos práticos do processo de integração de dados em um ambiente analítico primariamente utilizando recursos de SQL.

DETALHAMENTO:

Deve-se escolher conjuntos de dados para desenvolver análises (e.g., https://dados.gov.br/dados/conjuntos-dados, https://www.dados.pr.gov.br/, https://www.ibge.gov.br/acesso-informacao/dados-abertos.html e outros). Espera-se que sejam utilizados três ou mais conjuntos de dados diferentes, mas complementares, combinando dados de diferentes fontes e/ou datasets relacionados, enriquecendo o banco de dados. Por exemplo, coletar dados de uma mesma natureza, mas de provedores diferentes (e.g., dados de acidentes de trânsito de diferentes países), ou dados complementares (e.g., dados de censo escolar de um estado e combinados com dados de desempenho em avaliações, como IDEB).

Os conjuntos de dados devem contemplar dados nos formatos XML, JSON e tabulares. É fundamental vislumbrar consultas e relatórios relevantes que possam ser obtidos a partir dos conjuntos de dados coletados.

Implementar um esquema relacional de banco de dados para fazer o armazenamento integrado dos dados coletados, adotando um esquema analítico estrela, floco de neve ou constelação de estrelas. Os conjuntos de dados originais devem ser carregados em tabelas temporárias, utilizando alguma alternativa de carga (e.g., SQL Loader, scripts shell/Python, etc.). Em seguida, devem ser feitos os processamentos necessários utilizando SQL (SQL, SQL/XML, SQL/JSON), sempre que possível, para transportar os dados dos conjuntos de dados das tabelas temporárias para as tabelas do esquema analítico.

Por fim, definir e implementar consultas que produzam análises relevantes sobre os dados. Devem ser incluídas consultas que explorem diferentes recursos abordados na disciplina, incluindo agregações simples, uso de CASE/tratamento de nulos, operações OLAP, funções de janela, (materialized) views, etc.

ENTREGA:

25/05/2026 (segunda-feira) - A apresentação do trabalho será feita em sala, individualmente por grupo.

Antes da apresentação, deve ser submetido no Classroom um arquivo texto com todos os scripts, instruções e consultas desenvolvidos.

O trabalho pode ser feito em grupos de até 2 alunos. A avaliação considerará o arquivo com os scripts, instruções e códigos e a apresentação do grupo, com algumas demonstrações no banco desenvolvido. É fundamental que exista um balanceamento igualitário no grupo, em termos do conteúdo e complexidade das contribuições de cada um e também tempo e conteúdo na apresentação.

Cópias e trabalhos com uso significativo de IA para o desenvolvimento receberão nota zero.