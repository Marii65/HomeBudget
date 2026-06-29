# 💰 HomeBudget
## Sistema de controle financeiro familiar e individual

O **HomeBudget** é uma plataforma de gestão financeira desenvolvida para organizar gastos, entradas e saídas de uma casa ou família. O sistema permite controle coletivo das contas da família e também controle individual de despesas pessoais, proporcionando uma visão clara e organizada da vida financeira.

---

## ✨ Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

- Organização financeira familiar  
- Controle de despesas coletivas e individuais  
- Aprendizado de arquitetura Full Stack moderna  
- Implementação de autenticação segura e escalável  
- Prática de boas arquiteturas backend com Java  

---

## 🚀 Tecnologias Utilizadas

### 🐳 Docker
Utilizado para containerização do sistema

### 🔙 Backend
- Java  
- Spring Boot  
- Spring Security  
- JPA / Hibernate  
- API REST  
- JWT (Autenticação)  

### 🎨 Frontend
- React  
- Vite  
- JavaScript  
- Recharts (gráficos)  

### 🗄️ Banco de Dados
- MySQL  

---

## 👤 Funcionalidades do Sistema

### 🔐 Autenticação
- Cadastro de usuários  
- Login com JWT  
- Recuperação de senha (futuro)  
- Sessão persistente  
- Username único  
- Foto de perfil  

---

### 🏠 Sistema de Famílias
- Criação de uma família (casa)  
- Geração de código de convite  
- Entrada de membros via código  
- Administração por um ou mais usuários  

---

### 💸 Controle Financeiro Coletivo
Cada conta coletiva contém:

- Nome da conta  
- Valor  
- Data de vencimento  
- Responsável  
- Categoria  
- Status:
  - Pendente  
  - Pago  
  - Atrasado  

---

### 👤 Controle Financeiro Individual
- Cada usuário pode criar suas próprias contas pessoais  
- Visíveis apenas para o próprio usuário  

---

### 📊 Dashboard Financeiro
- Total do mês  
- Valor pago  
- Valor pendente  
- Gastos por categoria (gráficos)  
- Próximos vencimentos  
- Gastos por membro da família  

---

### 🎯 Sistema de Metas
- Em desenvolvimento  

### 🔔 Notificações
- Em desenvolvimento  

### 📄 Histórico Financeiro
- Em desenvolvimento  

### 📤 Exportação de Relatórios
- Em desenvolvimento  

---

### 🎨 UI/UX
- Interface moderna e responsiva  

---

## 🏗️ Estrutura do Projeto

```bash
homebudget
│
├── backend
│   ├── controller
│   ├── service
│   ├── repository
│   └── model
│
├── frontend
│   ├── components
│   ├── pages
│   ├── services
│   └── routes
│
└── README.md
