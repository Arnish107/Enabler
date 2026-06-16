# Enabler

Production-ready **Next.js 15** accessibility platform. Copy this folder into a GitHub repo named `enabler` and deploy to Vercel.

## Quick Start

```bash
npm install
cp .env.example .env.local
# Set JWT_SECRET (min 32 chars) and DATABASE_URL (optional)
npm run dev
npm run build
```

## Deploy to Vercel

1. Push to `github.com/YOUR_USERNAME/enabler`
2. Import repo at [vercel.com/new](https://vercel.com/new)
3. Add env vars: `JWT_SECRET`, `DATABASE_URL` (optional)
4. Click Deploy

## Stack

Next.js 15 · TypeScript · Tailwind CSS · shadcn/ui · Prisma · Vercel Serverless

## API Routes

| Route | Method | Description |
|-------|--------|-------------|
| `/api/speech` | POST | Speech-to-text |
| `/api/sign` | POST | Sign recognition |
| `/api/translate` | POST | Translation |
| `/api/upload` | POST | Video upload |
| `/api/alerts` | GET/POST | Sound alerts |
| `/api/health` | GET | Health check |

## All Project Files

See `GENERATED_FILES/` for every file in `FILE: path` format ready to copy.
