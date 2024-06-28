# Astro Starter Kit: Component Package

This is a template for an Astro component library. Use this template for writing components to use in multiple projects or publish to NPM.

```sh
npm create astro@latest -- --template component
```

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
├── index.ts
├── src
│   └── MyComponent.astro
│   └── Accordion.astro
├── tsconfig.json
├── package.json
```

The `index.ts` file is the "entry point" for your package. Export your components in `index.ts` to make them importable from your package.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command       | Action                                                                                                                                                                                                                           |
| :------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `npm link`    | Registers this package locally. Run `npm link my-component-library` in an Astro project to install your components                                                                                                               |
| `npm publish` | [Publishes](https://docs.npmjs.com/creating-and-publishing-unscoped-public-packages#publishing-unscoped-public-packages) this package to NPM. Requires you to be [logged in](https://docs.npmjs.com/cli/v8/commands/npm-adduser) |
