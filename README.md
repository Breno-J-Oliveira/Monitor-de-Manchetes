# 📰 Monitor de Manchetes em Tempo Real com Node.js e SQLite

<p align="center">
  <img src="https://img.shields.io/badge/Status-FINALIZADO-10B981?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Status Finalizado">
  <img src="https://img.shields.io/badge/Versão-1.0-2563EB?style=for-the-badge" alt="Versão 1.0">
  <img src="https://img.shields.io/badge/Projeto-Atividade%20Acadêmica-111827?style=for-the-badge" alt="Projeto Acadêmico">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/UI-Framer%20Style-111827?style=for-the-badge" alt="Framer Style">
</p>

---

## 📑 Índice

1. [Sobre o Projeto](#-sobre-o-projeto)
2. [Objetivo da Atividade](#-objetivo-da-atividade)
3. [Equipe de Desenvolvimento](#-equipe-de-desenvolvimento)
4. [Principais Funcionalidades](#-principais-funcionalidades)
5. [Tecnologias e Bibliotecas](#-tecnologias-e-bibliotecas)
6. [Estrutura do Projeto](#-estrutura-do-projeto)
7. [Interface (UI/UX)](#-interface-uiux)
8. [Requisitos de Execução](#-requisitos-de-execução)
9. [Como Rodar o Projeto](#-como-rodar-o-projeto)
10. [Observações sobre Git e node_modules](#-observações-sobre-git-e-node_modules)
11. [Contatos e Redes Sociais](#-contatos-e-redes-sociais)

---

# 🎯 Sobre o Projeto

O **Monitor de Manchetes** é um sistema de monitoramento automatizado de notícias em tempo real que utiliza técnicas de **Web Scraping** para coletar manchetes dos principais portais de notícias do Brasil, como:

- G1
- UOL
- CNN Brasil

As informações coletadas são processadas por um servidor desenvolvido em **Node.js** e armazenadas em um banco de dados local utilizando **SQLite**.

O projeto foi desenvolvido como atividade acadêmica para o curso de **Técnico em Desenvolvimento de Sistemas** da **Escola SENAI "A. Jacob Lafer"**.

---

# ⚙️ Objetivo da Atividade

O principal objetivo da atividade foi integrar múltiplas áreas do desenvolvimento web moderno em um único sistema funcional.

## O projeto envolveu:

### 🔹 Backend
Desenvolvimento de uma API REST utilizando **Express.js**.

### 🔹 Web Scraping
Extração automatizada de notícias utilizando:
- Axios
- Cheerio

### 🔹 Persistência de Dados
Armazenamento local utilizando:
- SQLite3

### 🔹 Frontend
Construção de uma interface moderna, minimalista e responsiva.

---

# 👥 Equipe de Desenvolvimento

Projeto desenvolvido em grupo por:

- **Breno José de Oliveira**
- **Gustavo Barreto**
- **Mariana F. Nascimento**

---

# 🏛️ Principais Funcionalidades

## ✅ Coleta Inteligente
- Captura automática de manchetes em tempo real.
- Tratamento de links e títulos.
- Organização das notícias por fonte.

## ✅ Banco de Dados Local
- Salvamento automático das notícias coletadas.
- Histórico persistente de consultas.

## ✅ Operações CRUD
### Create
Inserção automática das notícias no banco.

### Read
Listagem completa das notícias armazenadas.

### Delete
Remoção de registros específicos.

## ✅ Dashboard Moderno
- Interface em Dark Mode.
- Feedback visual em tempo real.
- Atualizações dinâmicas.

---

# 🛠 Tecnologias e Bibliotecas

| Tecnologia | Função |
|---|---|
| Node.js | Ambiente de execução |
| Express | Framework backend |
| Axios | Requisições HTTP |
| Cheerio | Parsing HTML e Scraping |
| SQLite3 | Banco de dados |
| Lucide Icons | Biblioteca de ícones |

---

# 🧠 Estrutura do Projeto

```text
monitor-noticias/
│
├── database/              # Banco de dados SQLite
│   └── noticias.db
│
├── public/                # Frontend
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── src/                   # Backend
│   ├── index.js           # Servidor principal
│   ├── db.js              # Configuração SQLite
│   └── scraper.js         # Web Scraping
│
├── package.json           # Dependências do projeto
├── package-lock.json
└── .gitignore
````

---

# 🎨 Interface (UI/UX)

A interface foi inspirada no design moderno da **Framer**, priorizando estética minimalista e experiência fluida.

## Características visuais:

### 🌑 Dark Mode Profundo

* Melhor legibilidade
* Menor fadiga visual

### 🪟 Glassmorphism

* Transparência
* Blur
* Efeito de vidro moderno

### ✨ Micro-interações

* Fade In
* Hover suave
* Loaders animados

---

# 💻 Requisitos de Execução

Antes de iniciar o projeto, você precisa ter instalado:

* **Node.js** (v14 ou superior)
* **NPM** (já incluso no Node.js)

---

# 🚀 Como Rodar o Projeto

## 1️⃣ Clone o repositório

```bash
git clone https://github.com/Breno-J-Oliveira/monitor-noticias.git
```

---

## 2️⃣ Entre na pasta do projeto

```bash
cd monitor-noticias
```

---

## 3️⃣ Instale as dependências

A pasta `node_modules` não é enviada ao GitHub por ser muito pesada.

Execute:

```bash
npm install
```

---

## 4️⃣ Inicie o servidor

```bash
node src/index.js
```

---

## 5️⃣ Acesse no navegador

Abra:

```text
http://localhost:3000
```

---

# ⚠️ Observações sobre Git e node_modules

A pasta `node_modules` foi adicionada ao `.gitignore` por ser extremamente pesada e específica para cada sistema operacional.

Essa é uma prática profissional adotada no mercado para:

* Manter o repositório leve
* Evitar conflitos entre ambientes
* Garantir instalação limpa das dependências

Todas as dependências podem ser recriadas utilizando:

```bash
npm install
```

---

## 🤝 Contatos e Redes Sociais
<p align="center">
  <a href="https://github.com/Breno-J-Oliveira" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
  </a>
  <a href="https://www.linkedin.com/in/breno-j-oliveira-672619352/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="https://www.instagram.com/brenoov" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
  </a>
  <a href="https://x.com/BrenoJOliveira_" target="_blank">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white">
  </a>
</p>

---

# 🏁 Conclusão Final

O **Monitor de Manchetes** demonstra como o ecossistema Node.js pode ser utilizado para criar aplicações modernas de automação e coleta de dados em tempo real.

O projeto integra:

* Web Scraping
* API REST
* Banco de dados relacional
* Interface moderna

Tudo isso em uma arquitetura simples, organizada e escalável.

A aplicação pode facilmente evoluir para:

* Sistemas profissionais de clipping
* Dashboards analíticos
* Plataformas de monitoramento de mídia
* Serviços automatizados de notícias

---

<p align="center">
  Desenvolvido com 💻 utilizando Node.js, Express e SQLite
</p>
