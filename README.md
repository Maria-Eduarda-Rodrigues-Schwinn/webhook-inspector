# Projeto Fullstack com IA

Este é um projeto fullstack que utiliza tecnologias modernas para criar uma aplicação web com uma API robusta e uma interface de usuário interativa. O projeto também explora o uso de inteligência artificial para melhorar a experiência do usuário.

## Tecnologias Utilizadas

### Backend (API)
- Node.js
- TypeScript
- Drizzle ORM
- Docker (com Docker Compose)

### Frontend (Web)
- React
- TypeScript
- Vite

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas em sua máquina:
- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- [pnpm](https://pnpm.io/)
- [Docker](https://www.docker.com/)

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/Maria-Eduarda-Rodrigues-Schwinn/webhook-inspector
   cd webhook-inspector
   ```

2. Instale as dependências do projeto:
   ```bash
   pnpm install
   ```

3. Configure as variáveis de ambiente:
   - Crie um arquivo `.env` na pasta `api/src` com as configurações necessárias.

## Uso

### Iniciar o Backend

1. Certifique-se de que o Docker está em execução.
2. Suba os serviços do backend com o Docker Compose:
   ```bash
   cd api
   docker-compose up
   ```

### Iniciar o Frontend

1. Navegue até a pasta `web`:
   ```bash
   cd web
   ```
2. Inicie o servidor de desenvolvimento:
   ```bash
   pnpm dev
   ```

A aplicação estará disponível em `http://localhost:5173`.

## Estrutura do Projeto

- `api/`: Contém o código do backend.
  - `src/db/`: Configuração do banco de dados e migrações.
  - `src/routes/`: Rotas da API.
- `web/`: Contém o código do frontend.
  - `src/`: Componentes e lógica da aplicação.

## Licença

Este projeto está licenciado sob a licença MIT.