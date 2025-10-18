# 🏋️‍♂️ Sistema de Gerenciamento de Academia
## Equipe:
- Guilherme Monteiro
- Rafael
- Paulo augusto
----

## 🧩 1. Visão Geral

Este projeto é um **sistema web leve e eficiente**, desenvolvido com foco em **Client-Side Rendering (CSR)** utilizando **React**.  
A aplicação foi idealizada para **automatizar e simplificar a gestão de academias**, centralizando as operações administrativas em uma interface intuitiva e moderna.

### 💡 Funcionalidades Principais

- 👤 **Alunos:** cadastro, edição e exclusão de dados pessoais  
- 💳 **Planos:** nome, valor, duração e descrição  
- 📅 **Assinaturas:** vínculo entre aluno e plano, com data de validade  
- 📍 **Check-ins:** registro de presença e frequência  
- 📊 **Relatórios:** resumo de pagamentos, presença e desempenho dos alunos  

> ⚙️ **Simples e direto:**  
> - Sem multiusuário / papéis complexos  
> - Sem autenticação avançada  
> - (Opcional) Login único de administrador com senha fixa definida no `.env`

---

## ⚙️ 2. Stack Simplificada

### 🖥️ Frontend (CSR)
- ⚛️ **React (Vite)** – desempenho e DX incríveis  
- 🧭 **React Router** – navegação SPA sem recarregamento  
- 🎨 **Tailwind CSS** – estilização rápida e responsiva  
- 🌐 **Axios / Fetch API** – consumo da API backend  

### 🧠 Backend
- 🟩 **Node.js + Express** – leve, flexível e fácil de manter  
- 🗄️ **SQLite + Prisma ORM** – banco de dados simples e eficiente   (monolitico)
- 🔐 **Autenticação simples (opcional)** – senha fixa para o painel  

---

## 🐳 3. Containerização (Docker)

O projeto é **totalmente containerizado**, garantindo portabilidade e facilidade no setup do ambiente.

