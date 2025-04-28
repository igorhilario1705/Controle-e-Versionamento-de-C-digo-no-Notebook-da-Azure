# Controle-e-Versionamento-de-C-digo-no-Notebook-da-Azure

Processo Aprendido
Introdução

Entendi que o Azure Databricks é uma plataforma de análise de dados baseada no Apache Spark, altamente escalável, que combina o melhor do Azure com o Databricks.
Foco principal: facilitar ciência de dados, engenharia de dados e machine learning com maior integração à nuvem da Microsoft.

Entendendo o Azure Databricks
Aprendi que o Databricks é organizado em Workspaces, Clusters e Notebooks.
Percebi que há uma forte relação com controle de versões (revisão e histórico de códigos nos notebooks, parecido com Git).
Destaque: o conceito de Delta Lake para transações ACID em dados no data lake.

Provisionando um Databricks
Vi que para iniciar é necessário criar um recurso Azure Databricks dentro do portal do Azure.
Provisionar um Databricks envolve configurar o plano de preços, região e criar um workspace.
Entendi que isso cria uma instância gerenciada, reduzindo preocupações com infraestrutura.

Criando um Cluster
Aprendi que o cluster é essencial para executar qualquer notebook: é nele que o Spark vai rodar.
Insight: É possível configurar clusters automáticos (para tarefas específicas) ou clusters interativos (para análise exploratória).
Também se destaca a importância de escolher o tipo de máquina (por exemplo, máquinas otimizadas para memória ou para processamento).
Usando Spark para Analisar Dados

Experimentei comandos em PySpark diretamente no notebook.
Percebi que o Databricks facilita a visualização dos dados com gráficos integrados no notebook.
Pude trabalhar com dados em CSV, JSON e também tabelas Delta.
Insights sobre DataFrame API, SQL no Spark e transformações distribuídas.
