# 📊 Análise de Dados de Vendas

Projeto de **análise exploratória de dados (EDA)** utilizando Python para analisar informações de vendas armazenadas em um banco de dados SQLite.

O objetivo do projeto é demonstrar como coletar, organizar, analisar e visualizar dados para gerar **insights de negócio**.

---

# 🎯 Objetivo

Realizar uma análise de dados de vendas para identificar:

* Total de vendas no período
* Categorias com maior faturamento
* Evolução das vendas ao longo do ano
* Mês com maior volume de vendas

---

# 🛠 Tecnologias utilizadas

* Python
* SQLite
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

# 📂 Estrutura do projeto

```
analise-de-dados
│
├── analises_de_dados.ipynb
└── README.md
```

---

# ⚙️ Funcionamento do projeto

O projeto segue as seguintes etapas:

### 1️⃣ Criação do banco de dados

Foi criado um banco de dados SQLite chamado:

```
dados_vendas.db
```

Com a tabela:

```
vendas1
```

Campos da tabela:

* id_venda
* data_venda
* produto
* categoria
* valor_venda

---

### 2️⃣ Inserção de dados de exemplo

Foram adicionados registros de vendas simuladas para diferentes categorias:

* Eletrônicos
* Roupas
* Livros

---

### 3️⃣ Carregamento dos dados

Os dados são carregados para um **DataFrame do Pandas** para facilitar a análise.

Exemplo:

```python
df_vendas = pd.read_sql('SELECT * FROM vendas1', conexao)
```

---

### 4️⃣ Análise dos dados

Foram realizadas análises como:

* Total de vendas no período
* Soma de vendas por categoria
* Identificação do mês com maior volume de vendas

Exemplo:

```python
vendas_categoria = df_vendas.groupby("categoria")["valor_venda"].sum()
```

---

### 5️⃣ Visualização dos dados

Foram criados gráficos para facilitar a interpretação dos dados.

Exemplo de visualizações:

* **Gráfico de barras** com vendas por categoria
* **Gráfico de linha** mostrando a evolução das vendas por mês

---

# 📈 Resultados da análise

Principais insights encontrados:

* A categoria **Eletrônicos apresentou o maior faturamento**.
* As categorias **Roupas e Livros tiveram menor participação**, porém com vendas consistentes.
* Foi possível identificar **meses com maior volume de vendas** ao longo do ano.

---

# 💡 Possíveis aplicações

Esse tipo de análise pode ajudar empresas a:

* Identificar produtos mais lucrativos
* Planejar campanhas de marketing
* Tomar decisões estratégicas baseadas em dados
* Identificar períodos de alta ou baixa demanda

---

# 🚀 Possíveis melhorias

* Utilizar datasets maiores
* Criar dashboards interativos
* Automatizar a análise com scripts
* Conectar com bases de dados reais

---

# 👨‍💻 Autor

Projeto desenvolvido por **Thalyson** como parte de estudos em **Engenharia de Software e Análise de Dados**.
