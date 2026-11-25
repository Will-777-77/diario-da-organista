# 🎹 Diário da Organista

> Aplicação web pensada especialmente para **professoras (instrutoras) de órgão da Congregação Cristã no Brasil (CCB)** e suas alunas, facilitando a organização de aulas, presença e planos de estudo em um ambiente simples e acolhedor.

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-f472b6?style=flat-square)
![React](https://img.shields.io/badge/React-19-61dafb?style=flat-square&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8-646cff?style=flat-square&logo=vite&logoColor=white)

---

## ✨ Sobre o projeto

O **Diário da Organista** nasceu com foco na rotina das **professoras de órgão da igreja CCB (Congregação Cristã no Brasil)**, reunindo em um só lugar a agenda de aulas, o controle de presença, os planos de estudo (métodos, escalas e hinos) e o acompanhamento do progresso de cada aluna.

---

## 🎯 Funcionalidades planejadas

### 🔐 Acesso e Perfis
- Tela de **Login e Cadastro**
- Acesso diferenciado para **Professora (Instrutora)** e **Aluna**

### 👩‍🏫 Painel da Professora
- Visão geral com indicadores (alunas ativas, aulas da semana e presença média)
- Lista de **próximas aulas** e status de confirmação
- Gestão de **Minhas Alunas** e **Aulas**
- Criação e acompanhamento de **Planos de Estudo** individuais
- **Relatórios** de evolução e **Configurações**

### 🎼 Painel da Aluna
- Visualização da **próxima aula** com confirmação de presença
- Checklist interativo do **Plano de Estudos** (estudos, escalas, métodos e hinos)
- Acompanhamento de **Minhas Aulas** e **Meu Progresso**
- Área de **Mensagens** e **Configurações**

---

## 🛠️ Tecnologias utilizadas

- **[React](https://react.dev/)** — Biblioteca para construção da interface
- **[Vite](https://vite.dev/)** — Ferramenta de build e servidor de desenvolvimento rápido
- **[React Router DOM](https://reactrouter.com/)** — Gerenciamento de rotas e navegação entre telas
- **[Lucide React](https://lucide.dev/)** — Biblioteca de ícones
- **[ESLint](https://eslint.org/)** — Padronização e análise estática de código

---

## 🚀 Como executar o projeto localmente

### Pré-requisitos
- [Node.js](https://nodejs.org/) instalado (versão LTS recomendada)
- [Git](https://git-scm.com/) instalado

### Passo a passo

```bash
# 1. Clone o repositório
git clone https://github.com/Will-777-77/diario-da-organista.git

# 2. Acesse a pasta do projeto
cd diario-da-organista

# 3. Instale as dependências
npm install

# 4. Inicie o servidor de desenvolvimento
npm run dev
```

Depois, abra no navegador o endereço exibido no terminal (geralmente `http://localhost:5173`).

---

## 📜 Scripts disponíveis

| Comando | Descrição |
| :--- | :--- |
| `npm run dev` | Inicia o servidor local em modo de desenvolvimento |
| `npm run build` | Gera a versão otimizada para produção na pasta `dist/` |
| `npm run preview` | Visualiza localmente a versão gerada pelo build |
| `npm run lint` | Executa o ESLint para verificar padrões de código |

---

## 📁 Estrutura inicial

```text
diario-da-organista/
├── public/          # Arquivos estáticos públicos
├── src/             # Código-fonte da aplicação React
│   ├── assets/      # Imagens, ícones e recursos visuais
│   ├── App.jsx      # Componente principal
│   └── main.jsx     # Ponto de entrada da aplicação
├── index.html       # HTML base
├── package.json     # Dependências e scripts
└── vite.config.js   # Configuração do Vite
```

---

Feito com dedicação para a rotina de estudos musicais. 🎶
