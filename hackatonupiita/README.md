# Steps taken

<a href="https://mirrorworld.fun/docs/overview/getting-started"> Link to the getting started </a>

We first need to create our account in the developer dashboard, and then create a project
in which we can find API keys, Client IDs, etc

### Managing your application credentials

All the projects count with this credentials:
1. **Api key**: Authorizes a client to access the Mirror API. And we can have mutiple API's
  for a single project. 
2. **Cliend ID**: Used to publicly identify our project and identify the request owner.
3. **Client secret**: A sensitive credential used to verify certain claims.

All this credentials are found in the project info, within the dashboard.

### Authenticate users with the mirror API 

<a href="https://mirrorworld.fun/docs/integration/js">Link to the steps</a>

This is a process just for the frontend, to allow the client access our application.

1. First we need to have our project which is the previous step
2. Then we need to install with 
```sh
npm install @mirrorworld/web3.js
```
  this will create the package.json,node modules and some env variables.


====================== ** This is the docs of the next js app **


This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
