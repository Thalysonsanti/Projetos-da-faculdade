# 📝 Sistema de Gestão de Notas

Projeto desenvolvido em Python para realizar o **cadastro de notas de alunos**, cálculo de média e exibição da situação final (Aprovado ou Reprovado).

O sistema funciona via **terminal**, permitindo registrar vários alunos e gerar um **resumo final da turma**.

---

# 🎯 Objetivo

Simular um sistema simples de gerenciamento de notas para demonstrar conceitos básicos de programação como:

* funções
* estruturas condicionais
* loops
* listas e dicionários
* tratamento de erros

---

# 🛠 Tecnologias utilizadas

* Python
* Jupyter Notebook / Google Colab

---

# 📂 Estrutura do projeto

```id="0gkvl7"
sistema-de-notas
│
├── Sistema_de_notas.ipynb
└── README.md
```

---

# ⚙️ Funcionamento do sistema

O programa permite registrar vários alunos e suas respectivas notas.

Fluxo do sistema:

1️⃣ O usuário digita o **nome do aluno**

2️⃣ O sistema solicita as **notas do aluno**

3️⃣ As notas são armazenadas em uma **lista**

4️⃣ O sistema calcula a **média das notas**

5️⃣ O aluno é classificado como:

* **Aprovado** → média maior ou igual a 7
* **Reprovado** → média menor que 7

6️⃣ É exibido um **relatório individual**

7️⃣ Ao final, o sistema mostra um **resumo da turma**

---

# 🧠 Regras do sistema

* As notas devem estar entre **0 e 10**
* O valor **-1 encerra o cadastro de notas**
* O usuário pode cadastrar **vários alunos**
* O comando **"sair" encerra o sistema**

---

# 📋 Exemplo de saída

```id="2g0jsc"
===== RELATÓRIO DO ALUNO =====
Aluno: Thalyson Santiago
Notas: [7.7, 8.0, 6.8, 7.0]
Média: 7.38
Situação: Aprovado
```

Resumo final da turma:

```id="skifed"
===== RESUMO FINAL DA TURMA =====
Thalyson Santiago - Média: 7.38 - Aprovado
Lucas Sampaio - Média: 6.88 - Reprovado
Flávia Santos - Média: 7.38 - Aprovado
```

---

# 🚀 Conceitos de programação utilizados

Durante o desenvolvimento foram aplicados:

* Criação de **funções**
* Uso de **listas para armazenar dados**
* Uso de **dicionários para organizar informações**
* **Tratamento de exceções** com `try/except`
* Estruturas de repetição `while`
* Estruturas condicionais `if/else`

---

# 🔧 Possíveis melhorias

Algumas evoluções possíveis para o sistema:

* Salvar os dados em **banco de dados**
* Criar uma **interface gráfica**
* Exportar resultados para **Excel ou CSV**
* Criar um sistema de **consulta de alunos**

---

# 👨‍💻 Autor

Projeto desenvolvido por **Thalyson** como parte dos estudos em **Engenharia de Software**.
