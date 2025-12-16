# 📓 Consultando.ipynb

Este notebook tem como objetivo demonstrar a **integração entre Python e SQL**, utilizando **Pandas** e **SQLAlchemy** para criação, consulta e análise de dados em um banco de dados **SQLite em memória**.

O projeto é voltado para fins **educacionais**, mostrando passo a passo como carregar dados, criar tabelas SQL e realizar consultas diretamente com SQL dentro do Python.

---

## 🚀 Tecnologias Utilizadas

* **Python 3**
* **Jupyter Notebook**
* **Pandas** – Leitura e manipulação de dados
* **Matplotlib** – Visualização de dados
* **SQLAlchemy** – Integração entre Python e SQL
* **SQLite** – Banco de dados relacional em memória

---

## 🌐 Fonte dos Dados

Os dados utilizados são carregados diretamente de arquivos CSV hospedados no GitHub da Alura:

* Itens de pedidos
* Pedidos
* Produtos
* Vendedores

Esses dados simulam um **cenário real de vendas**, permitindo análises relacionais entre tabelas.

---

## 🗄️ Estrutura do Projeto

### 1️⃣ Importação de Bibliotecas

O notebook inicia com a importação das bibliotecas necessárias para análise, visualização e conexão com banco de dados.

---

### 2️⃣ Carregamento dos Dados

Os arquivos CSV são lidos utilizando `pandas.read_csv()` diretamente a partir de URLs externas.

Exemplos de dados carregados:

* Pedidos
* Itens dos pedidos
* Produtos
* Vendedores

---

### 3️⃣ Criação do Banco de Dados

* Criação de um banco **SQLite em memória**
* Uso do `SQLAlchemy` para gerenciar a conexão
* Criação das tabelas a partir dos DataFrames

Isso permite executar consultas SQL sem necessidade de um banco físico.

---

### 4️⃣ Inspeção das Tabelas

* Verificação das tabelas criadas
* Conferência da estrutura do banco de dados

---

### 5️⃣ Consultas SQL

O notebook realiza diversas consultas SQL utilizando:

* `SELECT`
* `JOIN`
* `GROUP BY`
* `ORDER BY`
* Funções de agregação

As consultas são executadas diretamente no banco SQLite e os resultados retornam como **DataFrames Pandas**.

---

### 6️⃣ Análise e Visualização

* Análises exploratórias com Pandas
* Gráficos simples utilizando **Matplotlib** para apoiar a interpretação dos dados

---

## ▶️ Como Executar o Notebook

1. Clone o repositório:

```bash
git clone <url-do-repositorio>
```

2. Instale as dependências:

```bash
pip install pandas matplotlib sqlalchemy jupyter
```

3. Abra o notebook:

```bash
jupyter notebook Consultando.ipynb
```

---

## 🎯 Objetivo Educacional

Este notebook é ideal para quem deseja aprender:

* Como integrar **Python e SQL**
* Criar bancos de dados temporários
* Executar consultas SQL dentro do Python
* Transformar resultados SQL em análises com Pandas

---

## 📚 Possíveis Evoluções

* Persistir o banco em arquivo (`.db`)
* Criar visualizações mais avançadas
* Parametrizar consultas SQL
* Usar outros SGBDs (PostgreSQL, MySQL)

---

👨‍💻 Projeto indicado para estudos em **Data Science**, **Análise de Dados** e **SQL aplicado ao Python**.
