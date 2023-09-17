This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

### 1. Install Dependencies
```bash
npm install
```

### 2. Create EnvFile
```bash
cp .env.example .env.local
```

Add values of environment variables that you can find on Project Settings -> Service Accounts -> Generate new private Key



```
npm run dev
# or
yarn dev
```



### Deploy Inicial
`Instalar firebase CLI`
npm install -g firebase-tools
`Configurar projeto experimental`
firebase experiments:enable webframeworks
`Configurar projeto experimental`
firebase init hosting
Adicione o serviceAccount.json a raiz do projeto
npm run deploy_prod


### Problems

```This version of npm is compatible with lockfileVersion@1, but package-lock.json was generated for lockfileVersion@3.```
Instale a versão do global pelo npm



### un Local

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!


