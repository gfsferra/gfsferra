<h1 align="center">Gabriel Sferra</h1>

<p align="center">
  <strong>Desenvolvedor Full Stack</strong> · TypeScript, Vue, React Native e Laravel · Marília, SP
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gabriel-sferra-b3449021a/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:gfsferra35@gmail.com"><img alt="E-mail" src="https://img.shields.io/badge/E--mail-gfsferra35%40gmail.com-555?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://gabrielsferra.vercel.app"><img alt="Portfólio" src="https://img.shields.io/badge/Portfólio-gabrielsferra.vercel.app-222?style=flat-square&logo=vercel&logoColor=white"></a>
</p>

---

## Sobre mim

Sou desenvolvedor full stack, trabalho na [Tray](https://www.tray.com.br) e venho da área de testes de software. Esse começo pesa no meu jeito de construir: prefiro modelar os dados para que o banco recuse um estado inválido em vez de confiar que alguém vai lembrar de validar, gosto de tipos que atravessam do servidor ao cliente e concentro os testes onde um erro custaria caro.

Hoje me interesso por apps multiplataforma com uma única API, arquitetura serverless e qualidade de software.

## Projetos em destaque

### [Orbital](https://github.com/gfsferra/orbital)
Controle financeiro pessoal para iOS, Android e web, servido por uma única API headless.

`TypeScript` `Expo` `React Native` `Hono` `Drizzle` `Better Auth` `Cloudflare Workers` `PostgreSQL` `Zod`

- Contrato da API em schemas Zod compartilhados num monorepo: se o formato de uma resposta muda, o `tsc` do app quebra na hora.
- Dinheiro sempre em `bigint` (centavos) e lançamentos como `DATE`, sem erro de ponto flutuante nem de fuso.
- Chave estrangeira composta impede, já no banco, um gasto ligado a uma categoria de receita.
- 82 testes cobrindo o parsing de valores em pt-BR, os limites de mês e fuso e a geração idempotente de lançamentos recorrentes.

### [Cadastro Full Stack](https://github.com/gfsferra/fullstack)
Sistema de cadastro de usuários com login Google OAuth 2.0.

`Laravel 11` `Vue 3` `TypeScript` `MySQL` `Redis` `Docker`

- Repository Pattern e camada de serviços, com injeção de dependência pelos Service Providers.
- Refresh token automático, validação de CPF e paginação com filtros feita no servidor.
- E-mails enviados de forma assíncrona por filas no Redis; o ambiente inteiro sobe com Docker Compose.
- Testes unitários e de API com PHPUnit no back-end e Vitest no front-end.

### [ChromeOS Landing Page](https://gfsferra.github.io/chrome_os/Pages/)
Landing page responsiva em HTML, SCSS (arquitetura 7-1) e JavaScript, com build em Gulp. [Código](https://github.com/gfsferra/chrome_os)

## Tecnologias

<p>
  <img alt="Tecnologias" src="https://skillicons.dev/icons?i=ts,js,vue,react,nodejs,php,laravel,cs,postgres,mysql,redis,docker,cloudflare,tailwind,sass,git,linux&perline=9">
</p>

| Área | Ferramentas |
| --- | --- |
| Front-end | TypeScript, JavaScript, Vue 3, React, React Native (Expo), Tailwind CSS, SCSS |
| Back-end | Node.js (Hono), PHP (Laravel), C# (ASP.NET Core MVC) |
| Dados e infra | PostgreSQL, MySQL, Redis, Docker, Cloudflare Workers, Netlify |
| Qualidade | PHPUnit, Vitest, node:test, ESLint, testes manuais e exploratórios |

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gfsferra/gfsferra/output/github-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/gfsferra/gfsferra/output/github-snake.svg">
    <img alt="Animação de cobrinha percorrendo o gráfico de contribuições" src="https://raw.githubusercontent.com/gfsferra/gfsferra/output/github-snake.svg">
  </picture>
</p>
