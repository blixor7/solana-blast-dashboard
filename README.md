---

# Solana Blast Dashboard

A comprehensive analytics dashboard built with Next.js for monitoring Solana blockchain activity with integrated Twitter functionality.

## Quick Setup

Install dependencies:
```bash
npm install
```

Start development server:
```bash
npm run dev
```

Access the dashboard at `http://localhost:3000`

## Features

- **Solana Blockchain Analytics**: Real-time blockchain data visualization
- **Twitter Integration**: Social media connectivity for alerts and notifications
- **Leaderboard System**: User ranking and performance tracking
- **Mobile Responsive**: Optimized for all device sizes
- **Wallet Integration**: Secure wallet connection modal

## Tech Stack

- **Framework**: Next.js with App Router
- **Styling**: Tailwind CSS
- **Language**: TypeScript
- **Blockchain**: Solana Web3 integration
- **Social**: Twitter API integration

## Project Structure

```
src/                    # Application source code
public/                 # Static assets and images
├── app/                # Next.js app directory
├── components/         # Reusable UI components
└── utils/              # Utility functions

Configuration files:
- next.config.mjs       # Next.js configuration
- tailwind.config.ts    # Tailwind styling
- tsconfig.json         # TypeScript settings
```

## Development

The dashboard features:
- Real-time error handling for Twitter callbacks
- API integration for leaderboard data
- Mobile-responsive design improvements
- Enhanced wallet connection flow

## Deployment

Optimized for Vercel deployment with built-in Next.js optimization features.

```bash
npm run build
```

## Configuration

Includes ESLint and Prettier for code quality, with PostCSS for styling optimization.

---
