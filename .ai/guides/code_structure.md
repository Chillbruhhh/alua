# Code Structure & Modularity Guidelines

## 📏 File Size Limit
- **Max 500 lines per file**: When approaching this limit, refactor by splitting into smaller components, hooks, or utility files.
- **Reason**: Promotes readability, maintainability, and reduces cognitive load, adhering to the "Golden Rule" of modularity.

## 📂 Component Organization
- **One component per file**: Each React component should reside in its own `.tsx` file.
- **Named exports**: Prefer named exports over default exports for easier refactoring and clearer imports.
- **Co-located styles**: If a component has specific, non-global styles, they can be co-located within the component's file or a dedicated `component.module.css` if using CSS Modules (though Tailwind CSS is preferred).

## 🪝 Custom Hooks
- **All API calls and complex state logic**: Should be encapsulated within custom React hooks located in `/src/hooks/`.
- **Naming convention**: Hooks should start with `use` (e.g., `useAuth.ts`, `useSupabase.ts`).

## ✍️ TypeScript Usage
- **Mandatory for all files**: Strict TypeScript usage with proper type definitions.
- **Type Definitions**: All custom interfaces and types should be defined in `/src/types/`. Avoid `any` type whenever possible.

## 📦 Imports
- **Clear, consistent imports**: Prefer relative imports within packages (`./`, `../`) and absolute imports for root-level modules (`@/components/`). 