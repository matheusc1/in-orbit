# in.orbit 🌌

Aplicação full-stack desenvolvida com **React** e **Node.js** utilizando **TypeScript** para registro e acompanhamento de metas com progresso semanal.

## Funcionalidades ✨

- Cadastro de metas com número de execuções desejadas por semana.
- Marcação de metas como concluídas diariamente.
- Acompanhamento do progresso semanal das metas.

## Tecnologias Utilizadas 💻

### Front-end

- [React](https://react.dev/)
- [Typescript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Router](https://reactrouter.com/en/main)
- [Tanstack Query](https://tanstack.com/)
- [React Hook Form](https://react-hook-form.com/)
- [Zod](https://zod.dev/)

### Back-end

- [Nodejs](https://nodejs.org/en)
- [Typescript](https://www.typescriptlang.org/)
- [Drizzle ORM](https://orm.drizzle.team/)
- [Fastify](https://fastify.dev/)
- [Postgres](https://www.postgresql.org/)
- [Zod](https://zod.dev/)

## Instalação 🛠️

### Pré-requisitos

- Node.js instalado (versão recomendada: LTS).
- PostgreSQL configurado (é possível utilizar o [neon.tech](https://neon.tech/) para testar a aplicação, basta criar uma conta).

### Passo a passo

1. Clone o repositório e acesse a pasta do projeto:

```bash
git clone https://github.com/matheusc1/in-orbit
cd in-orbit
```

### Configuração do Back-end

2. Abra um novo terminal, acesse a pasta server e instale as dependências:

```bash
cd server
npm install
```

3. Execute o seed do banco de dados e inicie o servidor:

```bash
npm run seed
npm run dev
```

### Front-end

4. Na pasta raiz, instale as dependências:

```bash
npm install
```

5. Inicie a aplicação:

```
npm run dev
```

## Créditos 💡

Aplicação desenvolvida durante o evento **NLW** da [@Rocketseat](https://github.com/Rocketseat)