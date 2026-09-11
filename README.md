# Invoice Dashboard

An invoice management dashboard built while completing the [Next.js App Router course](https://nextjs.org/learn) — includes authentication, charts, and full CRUD for invoices.

## Features

- Login (NextAuth.js) protecting the dashboard
- Create, edit, and delete invoices (Server Actions)
- Search and pagination for the invoices list
- Revenue chart and summary cards
- Server-side form validation (Zod)
- Streaming UI with React Suspense (loading skeletons)

## Stack

- **Next.js 15** (App Router, Server Components, Server Actions)
- **TypeScript**
- **Tailwind CSS**
- **Postgres** (Neon) + `postgres.js`
- **NextAuth.js v5**
- Deployed on **Vercel**

## What I learned

This project walks through the core concepts of building a full-stack app with Next.js:

- **Styling** – different ways to style a Next.js app
- **Optimizations** – optimizing images, links, and fonts
- **Routing** – nested layouts and pages via file-system routing
- **Data Fetching** – setting up a Postgres database on Vercel, fetching and streaming data
- **Search and Pagination** – implemented with URL search params
- **Mutating Data** – using React Server Actions and revalidating the Next.js cache
- **Error Handling** – general and `404` not-found errors
- **Form Validation and Accessibility** – server-side validation and accessibility improvements
- **Authentication** – added with NextAuth.js
- **Metadata** – preparing the app for social sharing

## Running locally

\`\`\`bash
pnpm install
pnpm dev
\`\`\`

Requires a `.env` file with `POSTGRES_URL` and `AUTH_SECRET` (see `.env.example`).