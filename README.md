# AI Predictions Dashboard (Non-Betting)

A subscription-based AI predictions dashboard for fun and educational purposes.  
This project generates **AI predictions** on various topics, including basic topics for all users and premium topics for subscribers. It uses Node.js, Express, Socket.IO, MongoDB, Stripe, Discord, and TensorFlow.js.

---

## Features

- **User Authentication**: Sign up and log in with secure password hashing.
- **JWT Authorization**: Protects API routes and WebSockets.
- **AI Predictions**: Generates predictions for basic and premium topics.
- **Subscription System**: Stripe checkout for premium topics.
- **Real-time Updates**: WebSockets push latest predictions to connected users.
- **Discord & Social Integration**: Optional Discord notifications and social posting (console logging for now).
- **Frontend Dashboard**: Interactive web interface for login, subscription, and viewing predictions.

---

## Topics

### Basic Topics (free for all users)
- Sports Performance
- Weather Forecast

### Premium Topics (requires subscription)
- Stock Trend
- Fantasy Insights
- Random Fun Prediction

---

## Getting Started

### Prerequisites

- Node.js >= 18
- MongoDB (local or Atlas)
- Stripe account
- Discord bot token (optional)

---

### Installation

1. Clone the repository:

```bash
git clone https://github.com/6207jaden-cell/pballjaden-my-ai-app.git
cd pballjaden-my-ai-app
npm install
PORT=3000
MONGO_URI=your_mongodb_uri
STRIPE_SECRET=your_stripe_secret_key
STRIPE_PRICE_ID=your_stripe_price_id
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
DISCORD_TOKEN=your_discord_bot_token
DISCORD_CHANNEL_ID=your_discord_channel_id
JWT_SECRET=supersecret
node app.js
http://localhost:3000
