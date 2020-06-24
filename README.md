# styled-jsx + TypeScript Next.js example

This is an example project where the default export of styled-jsx/css causes warnings in build.

### Usage

Run `npm run build` or `yarn build` and notice the warnings in build output.

You can see that it gets fixed if you change the default export in `components/styles.tsx` to export a named variable.
