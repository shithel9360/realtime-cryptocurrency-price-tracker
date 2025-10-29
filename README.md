# Real-time Cryptocurrency Price Tracker

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![React](https://img.shields.io/badge/react-18.x-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Project Overview
Real-time Cryptocurrency Price Tracker provides live price updates, interactive charts, portfolio management, and market analysis for cryptocurrencies with WebSocket support and price alerts.

## Tech Stack
- **Frontend**: React.js, TypeScript, TradingView Charts
- **Backend**: Node.js, Express.js, WebSocket
- **Database**: MongoDB, Redis
- **Real-time Data**: WebSocket, CoinGecko API, Binance API
- **Charting**: Recharts, Chart.js, TradingView
- **Notifications**: Firebase Cloud Messaging
- **Testing**: Jest, Cypress, Supertest

## Features
- ✅ Real-time price updates
- ✅ Interactive price charts
- ✅ Portfolio tracking
- ✅ Price alerts and notifications
- ✅ Market cap rankings
- ✅ Historical data analysis
- ✅ Multiple cryptocurrency support
- ✅ Currency conversion
- ✅ Watchlist management
- ✅ Profit/loss calculations
- ✅ Market trends and news
- ✅ Dark/light themes

## Setup Instructions

### Prerequisites
- Node.js 16.x or higher
- MongoDB
- Redis

### Installation

```bash
# Clone the repository
git clone https://github.com/shithel9360/realtime-cryptocurrency-price-tracker.git
cd realtime-cryptocurrency-price-tracker

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your API keys (CoinGecko, Binance, etc.)

# Start MongoDB and Redis
# Make sure both are running

# Start backend server
cd backend
npm run dev

# In new terminal, start frontend
cd frontend
npm start
```

### Running Tests

```bash
# Run all tests
npm test

# Backend tests
cd backend && npm test

# Frontend tests
cd frontend && npm test

# E2E tests
npm run test:e2e
```

## Demo

![Demo GIF Placeholder](https://via.placeholder.com/800x400.png?text=Crypto+Tracker+Demo)

## API Documentation

API documentation available at `/api/docs`

## Supported Cryptocurrencies

- Bitcoin (BTC)
- Ethereum (ETH)
- And 5000+ other cryptocurrencies

## Contributing

Contributions welcome! See CONTRIBUTING.md.

## License

MIT License - see LICENSE file for details

## Contact

Shithel - [@shithel9360](https://github.com/shithel9360)
