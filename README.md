# 🖥️ SyncFlow — Frontend

Interface web do projeto SyncFlow, desenvolvida com **React 19**, **TypeScript** e **Tailwind CSS v4**. Utiliza as versões mais recentes do ecossistema front-end, com pipeline de qualidade configurado via Biome, Husky e Commitlint.

> 🔗 Repositório do backend: [SyncFlow-Backend](https://github.com/LeonardoMainardes/SyncFlow-Backend)

---

## ✨ Destaques técnicos

- **React 19** — versão mais recente do React com as últimas melhorias de performance e concorrência
- **TypeScript 5.9** — tipagem estática em toda a aplicação
- **Tailwind CSS v4** — nova versão do Tailwind com engine reescrita (via PostCSS), mais rápida e com menos configuração
- **Vite 8** — bundler de última geração para desenvolvimento ultra-rápido
- **Biome** — linter e formatter moderno substituindo ESLint + Prettier em uma única ferramenta
- **Husky + lint-staged** — garantia de qualidade no pre-commit
- **Commitlint** — padronização de commits com Conventional Commits

---

## 🛠️ Tecnologias utilizadas

![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)

---

## 🚀 Como rodar localmente

### Pré-requisitos

- [Bun](https://bun.sh/) ou Node.js 18+
- [SyncFlow-Backend](https://github.com/LeonardoMainardes/SyncFlow-Backend) rodando localmente

### 1. Clone o repositório

```bash
git clone https://github.com/LeonardoMainardes/SyncFlow-Frontend.git
cd SyncFlow-Frontend
```

### 2. Instale as dependências

```bash
# Com Bun (recomendado)
bun install

# Ou com npm
npm install
```

### 3. Configure as variáveis de ambiente

Crie um arquivo `.env` na raiz:

```env
VITE_API_URL=http://localhost:8888
```

### 4. Inicie o servidor de desenvolvimento

```bash
# Com Bun
bun run dev

# Ou com npm
npm run dev
```

Acesse `http://localhost:5173` no navegador.

---

## 📁 Estrutura do projeto

```
src/
├── components/     # Componentes reutilizáveis da UI
├── pages/          # Páginas e rotas da aplicação
├── services/       # Integração com a API do backend
├── hooks/          # Custom hooks React
├── types/          # Tipagens TypeScript globais
└── main.tsx        # Ponto de entrada da aplicação
```

---

## 🔧 Scripts disponíveis

| Comando | Descrição |
|---------|-----------|
| `bun run dev` | Inicia em modo desenvolvimento com HMR |
| `bun run build` | Gera o build de produção |
| `bun run preview` | Visualiza o build de produção localmente |
| `bun run lint` | Verifica o código com Biome |
| `bun run lint:fix` | Corrige automaticamente os problemas de lint |
| `bun run format` | Formata o código com Biome |

---

## 🔗 Integração com o backend

Este frontend se comunica com a [API REST do SyncFlow](https://github.com/LeonardoMainardes/SyncFlow-Backend), documentada via Swagger em `http://localhost:8888/docs`.

Certifique-se de ter o backend rodando antes de iniciar o frontend.

---

## 👨‍💻 Autor

Feito por **[Leonardo Mainardes](https://github.com/LeonardoMainardes)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/leonardomainardes)
