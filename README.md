# 💳 Sistema de Conta Bancária em TypeScript

Aplicação de console desenvolvida em **TypeScript** utilizando **Programação Orientada a Objetos (POO)**, simulando operações essenciais de um sistema bancário: criação de contas, consulta, atualização, exclusão, depósitos, saques e transferências.  
O projeto reforça conceitos como **herança**, **polimorfismo**, **classes**, **interfaces**, **controle de fluxo** e **boas práticas de organização de código**.

---

## 🚀 Tecnologias Utilizadas
- **TypeScript**
- **Node.js**
- **Readline-Sync** (interações no terminal)
- Estrutura de pastas modularizada (controller, model, repository, util)

---

## 🧱 Arquitetura do Projeto

src/

├── controller/

│ └── ContaController.ts # Regras de negócio e operações bancárias

├── model/

│ ├── Conta.ts # Classe abstrata base

│ ├── ContaCorrente.ts # Herança + limite especial

│ └── ContaPoupanca.ts # Herança + aniversário

├── repository/

│ └── ContaRepository.ts # Interface com os métodos obrigatórios

└── util/

└── Colors.ts # Cores para estilização do terminal
Menu.ts # Menu e execução da aplicação


---

## 📌 Funcionalidades

### 🔧 Controle de contas
- Criar conta corrente e conta poupança  
- Listar todas as contas existentes  
- Buscar conta pelo número  
- Atualizar dados de uma conta  
- Excluir conta  

### 💰 Operações financeiras
- **Saque**
- **Depósito**
- **Transferência entre contas**
- Regra de limite para conta corrente  
- Regra de aniversário para conta poupança  

### 🖥 Interface no terminal
- Menu interativo com **readline-sync**
- Textos coloridos com o módulo **Colors**
- Visualização formatada dos dados da conta

---

## ▶️ Como executar o projeto

1. Instale as dependências:
```bash
npm install
```
2. Execute a aplicação:
```bash
ts-node menu.ts
```

### Menu Principal 
<img width="385" height="344" alt="image" src="https://github.com/user-attachments/assets/7bf87d83-8c2c-4dea-9cfb-afdc24bb8fe9" />

### 🧠 Conceitos de POO aplicados
- Classe Abstrata: estrutura base para contas
- Herança: ContaCorrente e ContaPoupanca
- Polimorfismo: sobrescrita do método sacar()
- Interface: definição clara dos métodos obrigatórios

### 💬 Sobre mim
- 👩‍💻 Tayene Ramires 
- 🎓 Graduanda em Sistemas de Informação (FIT)
- 📍 Estudante da Generation Brasil — Full Stack JavaScript
- 💡 Em transição da área financeira para a tecnologia, apaixonada por lógica, dados e desenvolvimento de software.
