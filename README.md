# VEGA

VEGA — AI-powered business intelligence, automation, and digital transformation studio.

## Stack
- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- Framer Motion
- Prisma + PostgreSQL
- Resend

## Local setup

```bash
npm install
cp .env.example .env.local
npm run dev
```

Open http://localhost:3000.

For database-backed features:

```bash
npx prisma generate
npx prisma migrate dev
```

## Environment variables

Configure the values in `.env.local` using `.env.example` as the template. Never commit real API keys or database credentials.

## Main routes

- `/` — landing page
- `/contact` — contact/request page
- `/admin` — admin area
- `/api/leads` — lead submission API
- `/api/bookings` — booking API

## Project structure

```text
src/
  app/
  components/
  lib/
prisma/
middleware.ts
```
