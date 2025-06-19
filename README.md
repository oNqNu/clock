# Clock - Vite + React Hello World App

This is a simple Hello World application built with Vite and React.

## Getting Started

### Prerequisites

Make sure you have Node.js and pnpm installed on your system.

### Installation

1. Install dependencies:

```bash
pnpm install
```

2. Start the development server:

```bash
pnpm dev
```

3. Open your browser and navigate to `http://localhost:5173`

## Available Scripts

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm preview` - Preview production build
- `pnpm lint` - Run ESLint

## Features

- Hello World display
- Interactive counter button
- Hot Module Replacement (HMR)
- Modern React with hooks
- CSS Modules for scoped styling

## CSS Modules

This project uses CSS Modules for component-scoped styling. CSS Modules provide:

- Local scope for CSS classes
- No naming conflicts between components
- Better maintainability
- Type safety with TypeScript (when used)

### Usage Example

```jsx
import styles from './Component.module.css';

function Component() {
  return <div className={styles.container}>Content</div>;
}
```
