# Schulte Grid

A Next.js application for Schulte Grid - an attention and focus training exercise.

## Features

- Built with Next.js 14 (App Router)
- TypeScript for type safety
- Tailwind CSS for styling
- **Vercel Web Analytics** integrated for tracking page views and user interactions

## Vercel Web Analytics

This project has been configured with Vercel Web Analytics following the official documentation. The analytics are automatically tracked once deployed to Vercel.

### What's Configured

1. **Package Installed**: `@vercel/analytics` package has been added to dependencies
2. **Analytics Component**: The `<Analytics />` component from `@vercel/analytics/next` is included in the root layout (`app/layout.tsx`)
3. **Framework**: Using Next.js App Router integration as per Vercel's recommended approach

### How to Enable Analytics

After deploying to Vercel:

1. Navigate to your project's Analytics section in the Vercel Dashboard
2. Click the "Enable" button
3. Analytics will start collecting data automatically
4. View your analytics data in the Vercel Dashboard after deployment

### Local Development

Analytics work in development mode but data is not sent to Vercel. Deploy your application to see real analytics data.

## Getting Started

### Installation

```bash
pnpm install
```

### Development Server

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Build for Production

```bash
pnpm build
```

### Lint

```bash
pnpm lint
```

## Deployment

The easiest way to deploy this Next.js app is to use the [Vercel Platform](https://vercel.com):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

Once deployed, Vercel Web Analytics will automatically start tracking when enabled in your project settings.

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Vercel Analytics Documentation](https://vercel.com/docs/analytics)
- [Vercel Analytics Quickstart](https://vercel.com/docs/analytics/quickstart)
