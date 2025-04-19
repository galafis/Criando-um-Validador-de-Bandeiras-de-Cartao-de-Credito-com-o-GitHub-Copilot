# 💳 Detector de Bandeira de Cartão com IA

Esse projeto foi desenvolvido como parte de um desafio da DIO, com o objetivo de criar uma aplicação simples capaz de **identificar a bandeira de um cartão de crédito** (como Visa, MasterCard, Amex, etc.) a partir do número do cartão.

A ideia principal aqui foi usar o **GitHub Copilot** como um parceiro de codificação para acelerar o desenvolvimento, receber sugestões de código e aplicar boas práticas de programação com foco em **expressões regulares (Regex)**.

---

## 🎯 Objetivos

- Praticar lógica de programação usando expressões regulares
- Automatizar a detecção de bandeiras de cartões de crédito com base no número
- Explorar o uso do GitHub Copilot como assistente no processo de desenvolvimento
- Aprimorar o versionamento de código e documentação com GitHub

---

## 💻 Tecnologias Usadas

- Python 3.x
- Expressões Regulares (Regex)
- Git & GitHub
- GitHub Copilot (como assistente de codificação)

---

## 🚀 Como Funciona

O programa recebe como entrada um número de cartão de crédito (sem espaços ou traços) e verifica sua **bandeira** com base em padrões conhecidos. A lógica de detecção é feita com **expressões regulares**, por exemplo:

- `^4[0-9]{12}(?:[0-9]{3})?$` → Visa  
- `^5[1-5][0-9]{14}$` → MasterCard  
- `^3[47][0-9]{13}$` → American Express  
- (e assim por diante...)

---

## 📂 Estrutura do Projeto

```
📁 detector-bandeira-cartao
├── main.py             # Código principal do projeto
├── README.md           # Documentação do projeto
└── /images             # (Opcional) Capturas de tela da aplicação
```

---

## 📸 Imagens

(Opcional) Inclua aqui capturas de tela da aplicação rodando no terminal ou interface gráfica, se você criou uma.

---

## ✅ Resultado Esperado

Ao rodar o programa, o usuário insere um número de cartão e o sistema retorna a **bandeira identificada** com base no padrão.

Exemplo:

```
Digite o número do cartão: 4111111111111111  
Bandeira detectada: Visa
```

---

## 🧠 Aprendizados

Esse projeto foi ótimo pra reforçar:
- O uso de regex em problemas do mundo real
- Como o GitHub Copilot pode realmente acelerar o processo de desenvolvimento
- A importância de escrever código limpo, reutilizável e bem documentado

---

## 📌 Como Rodar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/detector-bandeira-cartao.git
cd detector-bandeira-cartao
```

2. Execute o programa:
```bash
python main.py
```

---

## 📚 Referências

- Documentação oficial do Python sobre `re` (regex)
- Regex101.com para testar expressões
- GitHub Copilot Docs

---

Feito com 💙 por um estudante apaixonado por dados, tecnologia e café ☕
