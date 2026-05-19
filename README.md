# inhaiku.lt

Retro Nokia-style news haiku generator built with Next.js and TypeScript.

![inhaiku.lt screenshot](/screenshot.png)

## What it is

- Fetches top news headlines and turns them into haiku poems.
- Uses a serverless API for news and AI generation.
- Mobile-first, retro UI inspired by old Nokia phones.

## Quick start

```sh
npm install
npm run dev
```

Open `http://localhost:3000`

## Environment

- `GOOGLE_API_KEY` — required for haiku generation

## Key files

- `app/page.tsx`, `app/layout.tsx` — main app shell
- `app/ui/ClientApp.tsx` — client-side UI
- `app/api/news/route.ts` — news headline API
- `app/api/haiku/route.ts` — haiku generation API
- `public/css/styles.css` — retro styling

## Features

- News headline to haiku conversion
- Country, category, and language selection
- Favorites and history support
- Social sharing
- Responsive retro UI

## API

- `GET /api/news` — fetch headlines by country/category
- `POST /api/haiku` — generate a haiku from a headline

## Deploy

```sh
vercel deploy
```

## License

MIT
