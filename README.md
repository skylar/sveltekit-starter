# sveltekit-starter

This is a project to bootstrap new apps using SvelteKit, Vite, TailwindCSS +
DaisyUI, and TypeScript. Simply fork this project and start building!

## How This Project Was Configured
This is a log of commands and steps taken to create this setup.

Note that in the first command, default options were selected to enable
Typescript, eslint, Prettier, Playwright, and Vitest.

```
pnpm create svelte@latest
pnpm install
pnpm add -D tailwindcss postcss autoprefixer
pnpm add daisyui
npx tailwindcss init tailwind.config.cjs -p

```

Additionally:

1. [File setup for TailwindCSS in SvelteKit](https://tailwindcss.com/docs/guides/sveltekit).
1. A default layout was setup with `#wrap` and `#content` elements.
1. Aliases were added to `svelte.config.js` for `$src` and `$lib` paths.
