This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
source start.sh
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Scripts

Runs next lint to set up Next.js' built-in ESLint configuration:
```bash
npm run lint 
```

## E2E Testing

To create the tests using Cepress run:
```bash
npm run cypress:open 
```

To run tests in CLI run:
```bash
npm run cy:run
```

To run tests from a single spec file use:
```bash
npm run cy:run -- --record --spec "cypress/e2e/my-spec.cy.js"
```


## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
