### Tauri SvelteKit TypeScript Boilerplate

Boilerplate for Tauri and SvelteKit projects in TypeScript

#### Prerequisites

- [Node.js](https://nodejs.org/) (^20.15)
- [pnpm](https://pnpm.io/) (^9.4)
- [Rust](https://www.rust-lang.org/) (^1.79)

#### Getting Started

1. Clone repo:

      ```bash
      git clone https://github.com/equilpres/tauri-sveltekit-typescript-boilerplate.git
      ```

2. Go to project dir:

      ```bash
      cd tauri-sveltekit-typescript-boilerplate
      ```

3. Install deps:

      ```bash
      pnpm install
      ```

#### Scripts

- `dev`: Start dev server.

     ```bash
     pnpm dev
     ```

- `tauri:dev`: Start Tauri.

     ```bash
     pnpm tauri:dev
     ```

- `build`: Build project.

     ```bash
     pnpm build
     ```

- `tauri:build`: Build Tauri.

     ```bash
     pnpm tauri:build
     ```

- `preview`: Preview prod build.

     ```bash
     pnpm preview
     ```

- `sync`: Sync files with SvelteKit.

     ```bash
     pnpm sync
     ```

- `svelte-check`: Check Svelte files.

     ```bash
     pnpm svelte-check
     ```

- `lint`: Lint code.

     ```bash
     pnpm lint
     ```

- `fmt`: Format code.

     ```bash
     pnpm fmt
     ```

- `bump`: Update deps.

     ```bash
     pnpm bump
     ```

- `tauri`: Access Tauri CLI.

     ```bash
     pnpm tauri
     ```

#### License

[MIT](LICENSE)
