# Forms with Next.js and Server Actions

This example shows how you can build forms with Next.js and Server Actions.

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init), [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/), or [pnpm](https://pnpm.io) to bootstrap the example:

```bash
npx create-next-app --example next-forms next-forms-app
```

```bash
yarn create next-app --example next-forms next-forms-app
```

```bash
pnpm create next-app --example next-forms next-forms-app
```

## Be sure to set this relation in your database of choice

```sql
CREATE TABLE todos (
  id SERIAL PRIMARY KEY,
  text TEXT NOT NULL
);
```

## Deploy your own

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/next.js/tree/canary/examples/next-forms&project-name=next-forms&repository-name=next-forms&stores=%5B%7B%22type%22%3A%22postgres%22%7D%5D)
