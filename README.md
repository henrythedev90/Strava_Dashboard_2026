# Strava Dashboard 2026

Full-stack marathon training dashboard built with Next.js, Supabase, and the Strava API. Tracks goal progress toward a sub-3:30 finish at the 99th Yonkers Marathon — featuring a live race countdown, 18-week training plan, Strava activity sync, video vlogs via Mux, and a race recap blog.

The app lives in [`pace-log/`](./pace-log/).

## Features

- **Race countdown** — live timer to race day
- **18-week training plan** — structured marathon prep
- **Strava sync** — activities pulled from the Strava API
- **Video vlogs** — upload and playback via Mux
- **Race recap blog** — MDX-powered posts

## Tech stack

| Layer | Tools |
| --- | --- |
| **Framework** | [Next.js](https://nextjs.org/) 16, [React](https://react.dev/) 19, [TypeScript](https://www.typescriptlang.org/) |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) 4 |
| **Backend & auth** | [Supabase](https://supabase.com/) (`@supabase/supabase-js`, `@supabase/ssr`) |
| **Integrations** | [Strava API](https://developers.strava.com/) (`strava-v3`), [Mux](https://www.mux.com/) (player, uploader, Node SDK) |
| **Maps** | [Mapbox GL](https://www.mapbox.com/mapbox-gljs) |
| **Data & UI** | [TanStack Query](https://tanstack.com/query), [SWR](https://swr.vercel.app/), [Recharts](https://recharts.org/), [Zod](https://zod.dev/) |
| **Content** | [MDX](https://mdxjs.com/) (`next-mdx-remote`, `@mdx-js/react`) |
| **Utilities** | [date-fns](https://date-fns.org/), [clsx](https://github.com/lukeed/clsx), [tailwind-merge](https://github.com/dcastil/tailwind-merge), [Lucide React](https://lucide.dev/) |
| **Tooling** | [pnpm](https://pnpm.io/), [ESLint](https://eslint.org/), [Prettier](https://prettier.io/), Supabase CLI |
