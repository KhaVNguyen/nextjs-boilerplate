# NextJS Boilerplate

Includes Eslint (with pre commit linting), Prettier, Styled Components

## Instructions

```
curl https://codeload.github.com/KhaVNguyen/nextjs-boilerplate/tar.gz/master | tar -xz nextjs-boilerplate
cd nextjs-boilerplate



yarn
yarn dev
```

## Notes

- Project related code is stored under a `src` folder.
  You can use either _relative_ imports or _absolute_ imports (where `src` is the base). An example of importing `BaseLayout` is shown in `index.tsx`

- ESLint will run automatically when saving files.

- Whenever you try to git commit, linting will be run on your staged files.
