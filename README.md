# HVAC Agent

Minimal landing page for HVAC workflows and dashboarding.

Includes Radix UI primitives, Tailwind 4, shadcn-inspired components, and telemetry via Vercel Analytics.

## Tech Stack

- Next.js 16 (App Router, Server/Client Components)
- React 19 + TypeScript 5
- Tailwind CSS 4, tailwind-merge, tailwindcss-animate
- Radix UI primitives, Vaul, Geist, Lucide icons
- React Hook Form + Zod, date-fns, recharts

## Getting Started

first-time setup

```sh
npm install
```

start dev server on http://localhost:3000

```sh
npm run dev
```

production build/serve

```sh
npm run build && npm start
```

Next lint rules

```sh
npm run lint
```

## Environment

```sh
# Copy .env.example to .env.local (if present) and populate required keys before running dev
cp .env.example .env.local
# (then edit .env.local as needed)
```

## Project Structure

- `app/` – Route segments, layouts, and pages
- `components/` – UI primitives and shared widgets
- `lib/` – Utilities and data helpers
- `styles/` – Global Tailwind/CSS files
- `public/` – Static assets

## Deployment

Optimized for Vercel. For self-hosting, run `npm run build` and serve `.next/standalone` behind your platform of choice. Ensure environment variables are configured in your target environment.
