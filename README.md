📈 StockSense — Alerts, Charts, AI Insights

An AI-powered modern stock market app built with Next.js, Shadcn, Better Auth, and Inngest! Track real-time prices, set personalized alerts, explore company insights, and manage watchlists. The admin dashboard allows managing stocks, publishing news, and monitoring user activity, while event-driven workflows power automated alerts, AI-driven daily digests, earnings notifications, and sentiment analysis—perfect for developers who want a dynamic, real-time financial platform.

📋 Table of Contents

✨ Introduction
⚙️ Tech Stack
🔋 Features
🤸 Quick Start
🔗 Assets
🚀 More

✨ Introduction

StockSense helps you stay ahead of the market by combining real-time financial data with AI-powered insights. Whether you're an individual trader or building tools for financial research, StockSense provides everything from live charts to automated workflows.

⚙️ Tech Stack

Better Auth → Authentication and authorization with email/password, social login, MFA.

CodeRabbit → AI-powered GitHub code review assistant.

Finnhub API → Real-time stock, forex, and crypto data.

Inngest → Event-driven workflows for alerts, digests, and notifications.

MongoDB → Flexible, scalable NoSQL database.

Nodemailer → Transactional emails and notifications.

Next.js → Full-stack React framework with SSR and API routes.

Shadcn → Accessible, customizable UI components.

TailwindCSS → Utility-first styling.

TypeScript → Type-safe JavaScript for better maintainability.

🔋 Features

👉 Stock Dashboard: Real-time prices with line & candlestick charts, historical data, and filtering by industry or market cap.
👉 Powerful Search: Quickly find stocks with intelligent search.
👉 Watchlist & Alerts: Personalized watchlists, thresholds for price/volume alerts, and instant email notifications.
👉 Company Insights: Financial data (PE ratio, EPS, revenue, analyst ratings, news, filings, sentiment).
👉 Real-Time Workflows: Automated event-driven tasks like price updates, digests, and AI-powered insights.
👉 AI-Powered Alerts & Summaries: Personalized market digests, earnings report notifications, and sentiment tracking.
👉 Customizable Notifications: Alerts based on user preferences and watchlists.
👉 Analytics & Insights: Track user behavior, stock trends, and engagement.

🤸 Quick Start
Prerequisites

Git

Node.js

npm



Install Dependencies
npm install

Set Up Environment Variables

Create a .env file in the project root:

NODE_ENV='development'
NEXT_PUBLIC_BASE_URL=http://localhost:3000

# FINNHUB
NEXT_PUBLIC_NEXT_PUBLIC_FINNHUB_API_KEY=
FINNHUB_BASE_URL=https://finnhub.io/api/v1

# MONGODB
MONGODB_URI=

# BETTER AUTH
BETTER_AUTH_SECRET=
BETTER_AUTH_URL=http://localhost:3000

# GEMINI
GEMINI_API_KEY=

# NODEMAILER
NODEMAILER_EMAIL=
NODEMAILER_PASSWORD=


Replace placeholders with real credentials (MongoDB, Gemini, Inngest, Finnhub).

Run the Project
npm run dev
npx inngest-cli@latest dev


Then open:
👉 http://localhost:3000

🔗 Assets

Logos, banners, and assets for StockSense are included in the assets folder.

🚀 More

Want to extend StockSense?

Add new financial data providers.

Implement portfolio tracking.

Expand admin features with deeper analytics.
