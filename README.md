# JengaBasePlate

| Dependency | Version |
|---|---|
| Svelte | 5.53.7 |
| Capacitor | 6.2.1 |
| Tailwind CSS | 4.2.1 |
| TypeScript | 5.9.3 |
| ESLint | 10.0.3 |
| Supabase JS | 2.98.0 |

A template project using Svelte + Capacitor + Tailwind CSS + TypeScript + Supabase, intended as a starting point for new projects.

## Getting Started

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Lint & Type-check

```bash
npm run lint
npm run check
```

## Supabase

Copy `.env.example` to `.env` and fill in your Supabase project URL and anon key:

```bash
cp .env.example .env
```

## Capacitor

After building, sync with native platforms:

```bash
npx cap add android   # or ios
npx cap sync
npx cap open android  # or ios
```
