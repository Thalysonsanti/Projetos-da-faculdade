# 📚 Sistema de Gerenciamento de Livros

Projeto desenvolvido em **Python** para realizar o cadastro, listagem e busca de livros, além da geração de gráficos para análise da quantidade de livros por gênero.

O sistema funciona através de um **menu interativo no terminal**, permitindo gerenciar um pequeno acervo de livros.

---

# 🎯 Objetivo

Criar um sistema simples de gerenciamento de livros para praticar conceitos fundamentais de programação como:

* Programação orientada a objetos (POO)
* Estruturas condicionais
* Estruturas de repetição
* Manipulação de listas
* Visualização de dados com gráficos

---

# 🛠 Tecnologias utilizadas

* Python
* Matplotlib
* Jupyter Notebook / Google Colab

---

# 📂 Estrutura do projeto

```id="0aagso"
sistema-livros
│
├── Sistema_livros.ipynb
└── README.md
```

---

# ⚙️ Funcionalidades do sistema

O sistema possui as seguintes funcionalidades:

### 📖 Cadastro de livros

Permite registrar um novo livro informando:

* Título
* Autor
* Gênero
* Quantidade disponível

---

### 📚 Listagem de livros

Exibe todos os livros cadastrados no sistema.

Exemplo de saída:

```id="69fyhz"
Título: Dom Casmurro, Autor: Machado de Assis, Gênero: Romance, Quantidade: 5
```

---

### 🔎 Busca de livro

Permite buscar um livro pelo **título**.

O sistema ignora diferenças entre **letras maiúsculas e minúsculas**.

---

### 📊 Geração de gráfico

O sistema gera um **gráfico de barras** mostrando a quantidade de livros cadastrados por gênero.

Esse recurso utiliza a biblioteca:

```id="dtyk7a"
matplotlib
```

---

# 🧠 Estrutura do código

O sistema utiliza uma **classe chamada `livro`** para representar cada livro.

Exemplo:

```python id="pdp1y3"
class livro:
    def __init__(self, titulo, autor, genero, quantidade):
        self.titulo = titulo
        self.autor = autor
        self.genero = genero
        self.quantidade = quantidade
```

Os objetos criados são armazenados em uma lista chamada:

```id="1sd9ti"
livros
```

---

# 🖥 Menu do sistema

O programa apresenta um menu com as opções:

```id="je07o2"
1 - Cadastrar livro
2 - Listar livros
3 - Buscar livro por título
4 - Gerar gráfico por gênero
5 - Sair
```

O usuário pode interagir com o sistema até escolher a opção **Sair**.

---

# 🚀 Possíveis melhorias

Algumas melhorias que poderiam ser implementadas:

* Salvar os livros em **banco de dados**
* Criar uma **interface gráfica**
* Permitir **edição ou exclusão de livros**
* Exportar relatórios em **CSV ou Excel**

---

# 👨‍💻 Autor

Projeto desenvolvido por **Thalyson** como parte dos estudos em **Engenharia de Software**.
