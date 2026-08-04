# TradeStak Starter

A polished React + TypeScript MVP frontend for TradeStak.

## Included pages

- Home
- Supplier directory
- Supplier profile
- Builder dashboard
- Pricing
- About
- Placeholder sign-in and demo pages

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Put this into Lovable

### Recommended method: GitHub

1. Create a new empty GitHub repository.
2. Upload every file and folder in this project to the repository root.
3. In Lovable, connect/import the GitHub repository.
4. Let Lovable install the dependencies.
5. Publish the project.

### Existing Lovable project

Back up or connect the current project to GitHub first. Then replace:

- `src/App.tsx`
- `src/main.tsx`
- `src/styles.css`

Add:

- `src/components.tsx`
- `src/data.ts`
- `public/tradestak-logo.png`
- `public/tradestak-app-icon.png`

Also merge or replace the included `package.json` dependencies and confirm the project uses Vite.

## Important

This is a frontend MVP with fictional demonstration data. Authentication, database persistence, reviews, saved suppliers, and AI responses should be connected to Supabase after the visual experience is approved.
