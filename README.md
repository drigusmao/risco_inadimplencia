#Projeto: risco_inadimplencia
pipeline dados desenvolvido em pyspark no databricks utilizando a arquitetura medalhao para analise de risco de credito
o que é o problema do negocio (risco de inadimplencia)

objetivo do projeto:
- identificar padroes de inadimplencia
-organizar dados brutos ate a camada analitica
-cria base pronta para consumo (bi / ml futuro)

tecnologia usadas
pyspark, delta lake, databricks , github

arquitetura medalhao:
o projeto utilza arquitetura medalhao para estruturar o pipeline
bronze ingestao dados brutos
silver limpeza e padronizacao
gold camada analitica pronta para consumo
documentacao completa arquitetura: 
docs/

diagrama estrutural:
o diagrama representa a estrutura consolidade da camada Silver, evidenciando entidades, chaves e relacionamento após o processo de tratamento dos dados.
talvez por a imagem
diagrama para vizualização:
docs/...

estrutura do projeto:
o projeto esta organizado de forma modular, separando a documentacao tecnica dos notebooks de processamento distribuidos por camdas (bronze, silver, gold), seguindo os principios da arquitetura medalhao.

risco_inadimplencia
│
├── README.md
│
├── Docs
│   ├── arquitetura_medalhao.md
│   ├── modelagem_dados.md
│   └── diagrama_silver.png
│
├── Notebooks
│   ├── 01__bronze
│   ├── 02__silver
│   └── 03__gold

