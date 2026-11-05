# BEQ Multi-Skill Staff

This is a Next.js application for managing multi-skill staff, integrated with Vercel Speed Insights for performance monitoring.

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Vercel Speed Insights

This project includes Vercel Speed Insights for monitoring real-user performance metrics. The `SpeedInsights` component is integrated in the root layout (`app/layout.tsx`).

### Features

- Real-time performance monitoring
- Core Web Vitals tracking
- Performance data visualization in Vercel dashboard

### Deployment

Deploy this app to Vercel to start collecting performance data:

```bash
vercel deploy
```

After deployment, you can view Speed Insights data in your Vercel dashboard under the "Speed Insights" tab.

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Vercel Speed Insights](https://vercel.com/docs/speed-insights)
