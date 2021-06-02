# Next.js example with TypeScript, ESLint, and Prettier

This is a really simple project that shows the usage of Next.js with TypeScript, ESLint and Prettier.

## How to use it?

### When creating a new Next.js project

```
$ npx create-next-app myapp --example https://github.com/maku77/template-nextjs-ts-eslint-prettier
```

### When developing

```
$ yarn dev    # Start Next.js dev server
$ yarn build  # Build for release
$ yarn lint   # Lint with Prettier and ESLint
$ yarn fix    # Autofix with Prettier and ESLint
```

When we run `next dev` the next time, Next.js will start looking for any `.ts` or `.tsx` files in our project and builds it.
Next.js has built-in TypeScript declarations, so we'll get autocompletion for Next.js' modules straight away.
