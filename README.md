### Tauri SvelteKit TypeScript Boilerplate

Minimalistic boilerplate for Tauri and SvelteKit projects in TypeScript.

#### Prerequisites

- [Node.js](https://nodejs.org/) (^18.18)
- [pnpm](https://pnpm.io/) (^8.15)
- [Rust](https://www.rust-lang.org/) (^1.77)

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

- `tauri::dev`: Start Tauri.

     ```bash
     pnpm tauri::dev
     ```

- `build`: Build project.

     ```bash
     pnpm build
     ```

- `tauri::build`: Build Tauri.

     ```bash
     pnpm tauri::build
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

This project is under the MIT License. See [LICENSE](LICENSE) for details.
