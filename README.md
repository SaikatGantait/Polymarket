# Polymarket

A decentralized prediction market platform built with React, TypeScript, and Solana.

## Features

- **Trading Interface**: Interactive market trading with real-time data
- **Copy Trading**: Follow and copy successful traders
- **Leaderboard**: Track top performers
- **Dashboard**: Overview of your positions and performance
- **Wallet Integration**: Connect with Solana wallets

## Technologies

- **Frontend**: React 18, TypeScript, Vite
- **UI Components**: shadcn-ui, Radix UI
- **Styling**: Tailwind CSS
- **Blockchain**: Solana Web3.js
- **State Management**: React Query, Context API
- **Backend**: Supabase

## Getting Started

### Prerequisites

- Node.js 18+ and npm (or use [nvm](https://github.com/nvm-sh/nvm#installing-and-updating))

### Installation

```sh
# Clone the repository
git clone <YOUR_GIT_URL>

# Navigate to the project directory
cd polymarket

# Install dependencies
npm install

# Start the development server
npm run dev
```

The application will be available at `http://localhost:8080`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Project Structure

```
polymarket/
├── src/
│   ├── components/     # React components
│   ├── pages/          # Page components
│   ├── hooks/          # Custom React hooks
│   ├── contexts/       # React contexts
│   ├── lib/            # Utility functions
│   └── integrations/   # External service integrations
├── supabase/           # Supabase functions and migrations
└── public/             # Static assets
```

## License

MIT
