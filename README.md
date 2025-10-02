# 💳 Detector de Bandeira de Cartão com IA

---

## 🇧🇷 Português

![Hero Image](images/card_validator_hero.png)

Esse projeto foi desenvolvido como parte de um desafio da DIO, com o objetivo de criar uma aplicação simples capaz de **identificar a bandeira de um cartão de crédito** (como Visa, MasterCard, Amex, etc.) a partir do número do cartão.

A ideia principal aqui foi usar o **GitHub Copilot** como um parceiro de codificação para acelerar o desenvolvimento, receber sugestões de código e aplicar boas práticas de programação com foco em **expressões regulares (Regex)**.

---

### 🎯 Objetivos

- Praticar lógica de programação usando expressões regulares
- Automatizar a detecção de bandeiras de cartões de crédito com base no número
- Explorar o uso do GitHub Copilot como assistente no processo de desenvolvimento
- Aprimorar o versionamento de código e documentação com GitHub

---

### 💻 Tecnologias Usadas

- Python 3.x
- Expressões Regulares (Regex)
- Git & GitHub
- GitHub Copilot (como assistente de codificação)

---

### 🚀 Como Funciona

O programa recebe como entrada um número de cartão de crédito (sem espaços ou traços) e verifica sua **bandeira** com base em padrões conhecidos. A lógica de detecção é feita com **expressões regulares**, por exemplo:

- `^4[0-9]{12}(?:[0-9]{3})?$` → Visa  
- `^5[1-5][0-9]{14}$` → MasterCard  
- `^3[47][0-9]{13}$` → American Express  
- (e assim por diante...)

---

### 📂 Estrutura do Projeto

```
📁 detector-bandeira-cartao
├── main.py             # Código principal do projeto
├── README.md           # Documentação do projeto
└── /images             # Imagens do projeto
```

---

### ✅ Resultado Esperado

Ao rodar o programa, o usuário insere um número de cartão e o sistema retorna a **bandeira identificada** com base no padrão.

Exemplo:

```
Digite o número do cartão: 4111111111111111  
Bandeira detectada: Visa
```

---

### 🧠 Aprendizados

Esse projeto foi ótimo pra reforçar:
- O uso de regex em problemas do mundo real
- Como o GitHub Copilot pode realmente acelerar o processo de desenvolvimento
- A importância de escrever código limpo, reutilizável e bem documentado

---

### 📌 Como Rodar

1. Clone o repositório:
```bash
git clone https://github.com/galafis/Criando-um-Validador-de-Bandeiras-de-Cartao-de-Credito-com-o-GitHub-Copilot.git
cd Criando-um-Validador-de-Bandeiras-de-Cartao-de-Credito-com-o-GitHub-Copilot
```

2. Execute o programa:
```bash
python main.py
```

---

### 📚 Referências

- Documentação oficial do Python sobre `re` (regex)
- Regex101.com para testar expressões
- GitHub Copilot Docs

---

Feito com 💙 por Gabriel Demetrios Lafis

---

## 🇬🇧 English

![Hero Image](images/card_validator_hero.png)

This project was developed as part of a DIO challenge, aiming to create a simple application capable of **identifying a credit card flag** (such as Visa, MasterCard, Amex, etc.) from the card number.

The main idea here was to use **GitHub Copilot** as a coding partner to accelerate development, receive code suggestions, and apply good programming practices with a focus on **regular expressions (Regex)**.

---

### 🎯 Objectives

- Practice programming logic using regular expressions
- Automate credit card flag detection based on the number
- Explore the use of GitHub Copilot as an assistant in the development process
- Improve code versioning and documentation with GitHub

---

### 💻 Technologies Used

- Python 3.x
- Regular Expressions (Regex)
- Git & GitHub
- GitHub Copilot (as a coding assistant)

---

### 🚀 How It Works

The program receives a credit card number (without spaces or hyphens) as input and verifies its **flag** based on known patterns. The detection logic is done with **regular expressions**, for example:

- `^4[0-9]{12}(?:[0-9]{3})?$` → Visa  
- `^5[1-5][0-9]{14}$` → MasterCard  
- `^3[47][0-9]{13}$` → American Express  
- (and so on...)

---

### 📂 Project Structure

```
📁 card-flag-detector
├── main.py             # Main project code
├── README.md           # Project documentation
└── /images             # Project images
```

---

### ✅ Expected Outcome

When running the program, the user enters a card number and the system returns the **identified flag** based on the pattern.

Example:

```
Enter card number: 4111111111111111  
Detected flag: Visa
```

---

### 🧠 Learnings

This project was great for reinforcing:
- The use of regex in real-world problems
- How GitHub Copilot can truly accelerate the development process
- The importance of writing clean, reusable, and well-documented code

---

### 📌 How to Run

1. Clone the repository:
```bash
git clone https://github.com/galafis/Criando-um-Validador-de-Bandeiras-de-Cartao-de-Credito-com-o-GitHub-Copilot.git
cd Criando-um-Validador-de-Bandeiras-de-Cartao-de-Credito-com-o-GitHub-Copilot
```

2. Execute the program:
```bash
python main.py
```

---

### 📚 References

- Official Python documentation on `re` (regex)
- Regex101.com for testing expressions
- GitHub Copilot Docs

---

Made with 💙 by Gabriel Demetrios Lafis
