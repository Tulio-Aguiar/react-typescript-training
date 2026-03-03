# react-typescript-training

Reciclagem técnica — React 19, TypeScript, Tailwind CSS | März 2026

## Stack

- **React 19** + **TypeScript**
- **Vite** (bundler)
- **Tailwind CSS v4**
- **React Router v7**
- **Zustand** (state management)
- **ESLint** + **Prettier**

## Project Structure

```
src/
├── assets/           # Static files: images, fonts, icons
├── components/
│   └── ui/           # Reusable primitive components (Button, Input, Modal...)
├── features/         # Feature-based modules (auth, dashboard, etc.)
├── hooks/            # Shared custom React hooks
├── layouts/          # Page layout wrappers (Header, Footer, Sidebar)
├── pages/            # Route-level components
├── routes/           # Route definitions and protected routes
├── services/         # API calls and external service integrations
├── store/            # Global state (Zustand)
├── types/            # Global TypeScript type declarations
├── utils/            # Pure utility/helper functions
└── styles/           # Global CSS and Tailwind base
```

## Getting Started

```bash
npm install
npm run dev
```

## Conventions

- **PascalCase** for components: `Button.tsx`, `UserCard.tsx`
- **camelCase** for hooks and utilities: `useAuth.ts`, `formatDate.ts`
- **kebab-case** for non-component files and folders when applicable
- Feature folders are self-contained: each has its own `components/`, `hooks/`, `types/`
- Shared hooks live in `src/hooks/` — component-specific hooks stay co-located
