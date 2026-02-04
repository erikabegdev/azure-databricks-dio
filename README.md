## 📝 Descrição

Este projeto, intitulado **Controle e Versionamento de Código no Notebook da Azure**, demonstra o uso do **Azure Databricks** para organização e execução de código em notebooks interativos, utilizando **Apache Spark**, **SQL** e **Python**.

O desenvolvimento foi **baseado no exercício “Explore Azure Databricks” do Microsoft Learn**, disponível em:  
https://microsoftlearning.github.io/mslearn-databricks/Instructions/Exercises/LA-01-Explore-Azure-Databricks.html

Durante o projeto, foram realizadas a importação de dados a partir de um arquivo CSV, a criação de tabelas no Databricks, a análise dos dados por meio de consultas SQL, o uso de **Spark DataFrames** e a geração de visualizações gráficas. Também foi explorado o **Databricks Assistant**, recurso de inteligência artificial integrado à plataforma, para apoio na compreensão e correção de código.

O projeto evidencia como notebooks do Azure Databricks permitem estruturar, organizar e acompanhar a evolução do código durante a análise de dados, servindo como uma introdução prática à plataforma no contexto de análise e engenharia de dados em nuvem.

## 📊 Etapas do Projeto

### 1️⃣ Importação de Dados
- Carregamento de um arquivo CSV de produtos disponibilizado pelo **Microsoft Learn** utilizando **pandas**
- O dataset contém **295 produtos**, com informações de **ID**, **nome**, **categoria** e **preço**

![01](https://github.com/user-attachments/assets/226e99ff-5a70-4e72-b0a7-295aa6dcbcef)

### 2️⃣ Conversão para Spark
- Conversão do **DataFrame pandas** para **Spark DataFrame**
- Criação de uma *view* temporária chamada **`products`** para permitir a execução de consultas SQL
  
![02](https://github.com/user-attachments/assets/24787842-9ec8-4d5f-a222-f8cc1fc3b853)


### 3️⃣ Análises e Filtros
- Filtragem de produtos com **preço acima de $100**, resultando em **205 produtos**
- Filtragem específica de produtos da categoria **"Road Bikes"**
- Visualização do dataset completo para análise exploratória

  ![03](https://github.com/user-attachments/assets/2e3e88f7-e8e4-4b00-8aa1-7733ab9c37fb)


### 4️⃣ Visualização
- Criação de um **gráfico de barras** para análise dos dados
- Visualização utilizada para apoiar a interpretação das informações por categoria de produto

![04](https://github.com/user-attachments/assets/f1427421-b29f-4c2a-9e26-6168ae9785e8)
![05](https://github.com/user-attachments/assets/c981e27f-79aa-4d98-b071-e59dde22151e)


## 🧰 Ferramentas Utilizadas

- **Azure Databricks** – Plataforma utilizada para criação e execução de notebooks em nuvem  
- **Apache Spark** – Engine de processamento distribuído para análise de dados  
- **Spark SQL** – Linguagem utilizada para consultas e exploração dos dados  
- **PySpark** – API Python do Apache Spark para manipulação de DataFrames  
- **Databricks Assistant** – Recurso de inteligência artificial integrado ao Databricks para auxílio na escrita e correção de código  
- **Microsoft Learn** – Fonte do exercício prático que serviu de base para o desenvolvimento do projeto  
- **GitHub** – Repositório utilizado para organização e compartilhamento do projeto
