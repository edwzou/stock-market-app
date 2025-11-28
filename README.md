# Stock Market App (Signalist)

A modern, real-time stock market tracking application built with Next.js, featuring TradingView widgets for comprehensive market data visualization.

## Features

- **Real-time Market Data**: Live stock prices and market information via TradingView widgets
- **Market Overview**: Comprehensive market performance dashboard
- **Stock Heatmap**: Visual representation of stock performance across the market
- **Market Quotes**: Real-time quotes and market data
- **Top Stories**: Financial news and market updates timeline
- **Dark Theme**: Modern dark mode interface
- **Responsive Design**: Optimized for desktop and mobile devices

## Tech Stack

- **Framework**: [Next.js 16](https://nextjs.org/) with App Router
- **UI Library**: React 19
- **Styling**: Tailwind CSS 4
- **UI Components**: Radix UI (Dropdown Menu, Avatar, Slot)
- **Icons**: Lucide React
- **Charts**: TradingView Widgets
- **Language**: TypeScript
- **Code Quality**: ESLint, Prettier

## Getting Started

### Prerequisites

- Node.js 20+ 
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd stock-market-app
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Project Structure

```
stock-market-app/
├── app/
│   ├── (root)/
│   │   ├── layout.tsx      # Root layout with Header
│   │   └── page.tsx         # Home page with TradingView widgets
│   ├── globals.css          # Global styles
│   └── layout.tsx           # Root HTML layout
├── components/
│   ├── ui/                  # Reusable UI components (Button, Avatar, Dropdown)
│   ├── Header.tsx           # Application header with navigation
│   ├── NavItems.tsx         # Navigation menu items
│   ├── TradingViewWidget.tsx # TradingView widget wrapper
│   └── UserDropdown.tsx     # User profile dropdown
├── hooks/
│   └── useTradingViewWidget.tsx  # Custom hook for TradingView widgets
├── lib/
│   ├── constants.ts         # Application constants and widget configs
│   └── utils.ts             # Utility functions
└── public/
    └── assets/              # Static assets (logos, images)
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Key Components

### TradingViewWidget
A reusable component that wraps TradingView widgets, providing a consistent interface for displaying market data, charts, and financial information.

### Header
The main navigation header featuring:
- Logo and branding
- Navigation menu (Dashboard, Search)
- User dropdown menu

## Development

The project uses:
- **TypeScript** for type safety
- **Tailwind CSS** for styling with custom configuration
- **ESLint** for code linting
- **Prettier** for code formatting

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [TradingView Widgets](https://www.tradingview.com/widget-docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Radix UI Documentation](https://www.radix-ui.com/)

## License

This project is private.
