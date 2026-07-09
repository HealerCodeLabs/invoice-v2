# Invoice V2

A modern Next.js application for invoice management with authentication and Prisma-backed persistence.

## Features

- Next.js 16 app router
- NextAuth authentication flows for sign in / sign up
- Prisma + SQLite (or configured database) for user and invoice data
- Tailwind CSS styling
- Auth-protected dashboard

## Getting Started

Install dependencies:

```bash
npm install
```

Generate Prisma client and run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Scripts

- `npm run dev` - start development server
- `npm run build` - generate Prisma client and build the app
- `npm run start` - start the production server
- `npm run lint` - run ESLint
- `npm run prisma:generate` - generate Prisma client
- `npm run prisma:migrate` - run Prisma migrations locally
- `npm run prisma:deploy` - deploy Prisma migrations

## Project Structure

- `src/app/` - application routes and pages
- `src/components/` - reusable React components
- `src/lib/` - authentication and Prisma helpers
- `src/prisma/schema.prisma` - Prisma schema

## Authentication

This app includes sign in and sign up pages under:

- `/auth/signin`
- `/auth/signup`

After signing in, the dashboard is available at `/dashboard`.

## Notes

This project is configured for Next.js v16 with Tailwind CSS v4 and Prisma v7.
