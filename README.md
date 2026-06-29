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

- Autenticação
- Sistema de Famílias
- Controle Financeiro Coletivo
- Controle Financeiro Individual
- Dashboard Financeiro
- Sistema de Metas
- Notificações
- Histórico Financeiro
- Exportação de Relatórios
- UI/UX

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
```
## ⚙️ Como Executar o Projeto

### 📦 Pré-requisitos
- Docker e Docker Compose instalados  
- *(Opcional)* Node.js 18+ para desenvolvimento local  
- *(Opcional)* Java 17+ para execução fora do Docker  

Este projeto pode ser executado completamente via Docker, sem necessidade de instalar dependências locais.

---

## 🐳 Subir a aplicação via Docker

Na raiz do projeto:

```bash
docker compose up --build
```
## 🌐 Acesso à aplicação
```bash
**Frontend:**  
http://localhost:5173  

**Backend API:**  
http://localhost:8080  
```
---

## 🖥️ Subir a aplicação de forma manual

**Backend:**
```bash
mvn spring-boot:run
```
**Frontend**
```bash
npm i
npm run dev
```
## 📌 Status do Projeto
*Em desenvolvimento*

## 👨‍💻 Autor 
*Desenvolvido por Mari* 
*Projeto pessoal para estudo de desenvolvimento Full Stack com Java e React.*
