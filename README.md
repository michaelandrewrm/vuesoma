# Vuesoma

Vuesoma is a custom development environment based on Vite + Vue 3 ecosystem that helps you out to start creating a single page application with the following features:

- Routing with [vue-router](https://router.vuejs.org)
- Store management with [pinia](https://pinia.vuejs.org)
- Internationalization with [vue-i18n](https://vue-i18n.intlify.dev)
- Styling with [Tailwind](https://tailwindcss.com)
- Code formatting with [Prettier](https://prettier.io)
- Code analyzing with [ESLint](https://eslint.org)
- Unit testing with [Vites](https://vitest.dev)
- e2e tests with [Cypress](https://www.cypress.io)

---

<br>

> Recommended IDE setup: [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

> Customize configuration: See [Vite Configuration Reference](https://vitejs.dev/config/).

<br>

# Project setup:

```sh
git clone https://github.com/michaelandrewrm/vuesoma
cd vuesoma
npm install
```

Compile and Hot-Reload for development

```sh
npm run dev
```

Compile and minify for production

```sh
npm run build
```

Run unit tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run end-to-end tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments):

```sh
npm run build
npm run test:e2e
```

Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
