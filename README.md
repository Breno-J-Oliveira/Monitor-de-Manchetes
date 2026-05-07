Com base no seu modelo anterior e em todo o trabalho que realizamos para deixar o código impecável, aqui está o seu **README.md** profissional, completo e seguindo a estética que você gosta.

---

# 📰 Monitor de Manchetes em Tempo Real com Node.js e SQLite

<p align="center">
  <img src="[https://img.shields.io/badge/Status-FINALIZADO-10B981?style=for-the-badge&logo=checkmarx&logoColor=white](https://img.shields.io/badge/Status-FINALIZADO-10B981?style=for-the-badge&logo=checkmarx&logoColor=white)">
  <img src="[https://img.shields.io/badge/Versão-1.0-2563EB?style=for-the-badge](https://img.shields.io/badge/Versão-1.0-2563EB?style=for-the-badge)">
  <img src="[https://img.shields.io/badge/Projeto-Atividade%20Acadêmica-111827?style=for-the-badge](https://img.shields.io/badge/Projeto-Atividade%20Acadêmica-111827?style=for-the-badge)">
</p>

<p align="center">
  <img src="[https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)">
  <img src="[https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)">
  <img src="[https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)">
  <img src="[https://img.shields.io/badge/UI-Framer%20Style-black?style=for-the-badge](https://img.shields.io/badge/UI-Framer%20Style-black?style=for-the-badge)">
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
11. [Contatos](#-contatos-e-redes-sociais)

---

## 🎯 Sobre o Projeto
Este é um sistema de monitoramento de notícias automatizado que utiliza técnicas de **Web Scraping** para extrair manchetes em tempo real dos maiores portais do Brasil (G1, UOL e CNN Brasil). Os dados coletados são processados por um servidor Node.js e persistidos em um banco de dados relacional leve (SQLite).

Projeto desenvolvido para o curso de **Técnico em Desenvolvimento de Sistemas** na **Escola SENAI "A. Jacob Lafer"**.

---

## ⚙️ Objetivo da Atividade
A atividade teve como foco a integração de múltiplas camadas de desenvolvimento:
- **Backend:** Construção de uma API REST com Express.
- **Data Scraping:** Extração de dados via Axios e Cheerio.
- **Persistência:** Implementação de operações de CRUD em SQLite.
- **Frontend:** Criação de uma interface reativa e minimalista.

---

## 👥 Equipe de Desenvolvimento
Este projeto foi realizado em grupo por:
- **Breno José de Oliveira**
- **Gustavo Barreto**
- **Mariana F. Nascimento**

---

## 🏛️ Principais Funcionalidades
- **Coleta Inteligente:** Extração de manchetes principais com tratamento de URLs e títulos.
- **Banco de Dados Local:** Armazenamento automático de cada consulta para histórico.
- **Operações CRUD Completas:**
  - **Create:** Captura e inserção automática de notícias.
  - **Read:** Listagem histórica das notícias salvas.
  - **Delete:** Remoção de registros específicos do monitoramento.
- **Dashboard Moderno:** Visualização em modo dark com feedback em tempo real.

---

## 🛠 Tecnologias e Bibliotecas
- **Node.js:** Ambiente de execução.
- **Express:** Framework web para gerenciamento de rotas e arquivos estáticos.
- **Axios:** Para requisições HTTP aos portais de notícias.
- **Cheerio:** Para parsing e manipulação do HTML (Scraping).
- **SQLite3:** Banco de dados relacional para persistência local.
- **Lucide Icons:** Biblioteca de ícones minimalistas.

---

## 🧠 Estrutura do Projeto
A organização segue padrões profissionais de separação de responsabilidades:

```text
monitor-noticias/
├── database/          # Arquivo do banco de dados SQLite (.db)
├── public/            # Frontend (HTML, CSS Framer-like, JS Client)
├── src/               # Backend (Lógica do Servidor)
│   ├── index.js       # Ponto de entrada e rotas da API
│   ├── db.js          # Configuração e funções do SQLite
│   └── scraper.js     # Lógica de extração das notícias
├── package.json       # Definição de dependências e scripts
└── .gitignore         # Arquivos ignorados pelo Git (node_modules)
```

---

## 🎨 Interface (UI/UX)
A interface foi inspirada no design da **Framer**, utilizando:
- **Dark Mode Profundo:** Foco em legibilidade e redução de fadiga visual.
- **Glassmorphism:** Efeitos de desfoque e transparência em cards.
- **Micro-interações:** Animações de entrada (Fade In), loaders de carregamento e estados de hover orgânicos.

---

## 💻 Requisitos de Execução
- **Node.js** instalado (versão 14 ou superior).
- **NPM** (gerenciador de pacotes que vem com o Node).

---

## 🚀 Como Rodar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Breno-J-Oliveira/monitor-noticias.git
   ```

2. **Entre na pasta do projeto:**
   ```bash
   cd monitor-noticias
   ```

3. **Instale as dependências (IMPORTANTE):**
   A pasta `node_modules` não é enviada ao GitHub por ser muito pesada. Você deve recriá-la rodando:
   ```bash
   npm install
   ```

4. **Inicie o servidor:**
   ```bash
   node src/index.js
   ```

5. **Acesse no navegador:**
   Abra [http://localhost:3000](http://localhost:3000)

---

## ⚠️ Observações sobre Git e node_modules
Como este projeto utiliza Node.js, a pasta `node_modules` foi adicionada ao arquivo `.gitignore`. Isso é uma **boa prática de mercado**, pois garante que o repositório seja leve e que cada desenvolvedor instale as dependências corretas para seu próprio sistema operacional através do comando `npm install`.

---

## 🤝 Contatos e Redes Sociais
**Breno José de Oliveira**

<p align="center">
  <a href="[https://github.com/Breno-J-Oliveira](https://github.com/Breno-J-Oliveira)" target="_blank">
    <img src="[https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)">
  </a>
  <a href="[https://www.linkedin.com/in/breno-j-oliveira-672619352/](https://www.linkedin.com/in/breno-j-oliveira-672619352/)" target="_blank">
    <img src="[https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)">
  </a>
</p>

**Professores Responsáveis:** Paulo Camargo e Raul Porto.

---

## 🏁 Conclusão Final
O "Monitor de Manchetes" demonstra como o Node.js pode ser poderoso para tarefas de automação e coleta de dados. O projeto une a robustez do SQLite com uma interface moderna, resultando em uma ferramenta funcional que poderia ser facilmente escalada para um serviço de clipping profissional.

---
