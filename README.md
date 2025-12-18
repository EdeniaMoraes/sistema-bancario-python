# Sistema Bancário Otimizado com Funções em Python

Este projeto é uma versão aprimorada do sistema bancário básico, implementando conceitos de funções, modularização e regras de passagem de argumentos (Positional Only e Keyword Only) em Python.

## 🚀 Novas Funcionalidades

- **Criação de Usuários:** Cadastro de clientes com CPF único.
- **Criação de Contas:** Vinculação de contas correntes a usuários cadastrados.
- **Depósito:** Operação via argumentos posicionais.
- **Saque:** Operação via argumentos nomeados (Keyword Only).
- **Extrato:** Exibição de histórico com argumentos mistos.

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**

## 📝 Regras de Negócio

- O CPF deve conter apenas números e ser único para cada usuário.
- Cada conta possui uma agência fixa (0001) e número sequencial.
- Limite de 3 saques diários de no máximo R$ 500,00 cada.
