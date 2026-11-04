# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and Biome for linting and formatting.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is enabled on this template. See [this documentation](https://react.dev/learn/react-compiler) for more information.

Note: This will impact Vite dev & build performances.
You can also try [the experimental native React Compiler support in plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md#rust-react-compiler) by using `compiler: true` in the plugin options instead of using the Babel plugin.

## Linting and formatting

This project uses [Biome](https://biomejs.dev) for linting, formatting and import sorting. Configuration lives in `biome.json`.

- `pnpm lint` checks lint rules, formatting and import order
- `pnpm format` applies fixes and formatting

See the [Biome rules documentation](https://biomejs.dev/linter/rules/) for the full list of rules.
