9# vuejs.org

## Contributing

This site is built with [VitePress](https://github.com/vuejs/vitepress) and depends on [@vue/theme](https://github.com/vuejs/vue-theme). Site content is written in Markdown format located in `src`. For simple edits, you can directly edit the file on GitHub and generate a Pull Request.

For local development, [pnpm](https://pnpm.io/) is preferred as package manager:

```bash
pnpm i
pnpm run dev
```

This project requires Node.js to be `v18` or higher. And it is recommended to enable corepack:

```bash
corepack enable
```

## Working on the content

- See VitePress docs on supported [Markdown Extensions](https://vitepress.dev/guide/markdown) and the ability to [use Vue syntax inside markdown](https://vitepress.dev/guide/using-vue).

- See the [Writing Guide](https://github.com/vuejs/docs/blob/main/.github/contributing/writing-guide.md) for our rules and recommendations on writing and maintaining documentation content.

## Working on the theme

If changes need to made for the theme, check out the [instructions for developing the theme alongside the docs](https://github.com/vuejs/vue-theme#developing-with-real-content).
