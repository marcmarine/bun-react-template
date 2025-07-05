# React Template

A minimal starter project using **React** with **Bun** as runtime and build tool.

[![Deploy to Pages](https://github.com/marcmarine/react-template/actions/workflows/deploy.yml/badge.svg?branch=main)](https://github.com/marcmarine/react-template/actions/workflows/deploy.yml)

With this template, you can either:

- Generate a static Single Page Application (SPA) ready to be deployed on any static hosting service.

- Run a backend server that serves both your API and your React frontend together.

## Quick Start

```bash
bun create marcmarine/react-template
cd react-template
bun dev
```

## Available Scripts

### `bun run dev` — Development (Hot Reload)

Run the app in development mode with hot module reloading:

```bash
bun dev
```

### `bun run build` — Build Static Site

Generates a production-ready static Single Page Application (SPA):

```bash
bun run build
```

- Outputs files to the `/dist` directory.

- Minifies code and includes sourcemaps.

- Supports environment variables starting with `BUN_PUBLIC_*`.

> [!NOTE]
> This command only generates static files (HTML, JS, CSS). You can deploy them to any static file server, such as GitHub Pages.

### `bun run start` — Backend Server + Frontend

Runs the project in production mode using Bun to serve both backend (if any) and frontend.

```bash
bun run start
```

- Executes `src/backend.tsx` as the backend entry point.

- Can include backend logic along with serving the frontend.

> [!NOTE]
> Unlike `build`, this command starts a server to serve the app.

## Credits

This project was created using `bun init` in bun v1.2.5. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.
