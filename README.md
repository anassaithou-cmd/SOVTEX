# SOVTEX

AI-powered ecosystem for Digital Workers and E-commerce entrepreneurs.

## Getting Started

First, install dependencies:

```bash
npm install
```

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Email verification setup

To send real verification emails, copy `.env.example` to `.env.local` and update the SMTP settings:

```bash
cp .env.example .env.local
```

Then set your SMTP provider values for:

- `SMTP_HOST`
- `SMTP_PORT`
- `SMTP_USER`
- `SMTP_PASSWORD`
- `EMAIL_FROM`

The waitlist verification email will be sent from `anassaithou@gmail.com` by default.

## Project Structure

- `src/app/` - Next.js App Router pages
- `src/components/` - Reusable components
- `src/config/` - Configuration files including theme

## Features

- Home page with hero and feature grid
- Blog page with knowledge base articles
- Resources page with curated tools
- Responsive design with custom theme
