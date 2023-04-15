# vite-plugin-dist-css

This plugin will inject css into bundled js file using `import` statement.

```js
// bundled js file, with import css at top (if any)
import './style.css';
// rest of the file
// ...
```

## install

```shell
# npm
npm i @elonehoo/vite-plugin-dist-css
# yarn
yarn add @elonehoo/vite-plugin-dist-css
# pnpm
pnpm install @elonehoo/vite-plugin-dist-css
```

## usage

```ts
// vite.config.ts
import distCss from '@elonehoo/vite-plugin-dist-css'

// https://vitejs.dev/config/
export default defineConfig({
  plugins: [
    // any other plugins
    distCss()
  ],
})
```
