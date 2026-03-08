# JengaBasePlate

## Stack
- **Svelte** 5.53.7 (via Vite 6)
- **Capacitor** 6.2.1
- **Tailwind CSS** 4.2.1
- **TypeScript** 5.9.3
- **ESLint** 10.0.3 (with eslint-plugin-svelte + typescript-eslint)
- **Supabase** JS SDK 2.98.0

## Project Structure
- `src/` — Svelte application source
  - `src/lib/supabase.ts` — Supabase client (reads from `VITE_SUPABASE_URL` / `VITE_SUPABASE_ANON_KEY`)
- `public/` — Static assets
- `dist/` — Build output (git-ignored)
- `project/` — Project management (epics, stories, tasks)
- `documentation/` — Project documentation and plans

## Scripts
- `npm run dev` — Start dev server
- `npm run build` — Production build
- `npm run check` — Svelte type-check
- `npm run lint` — ESLint
