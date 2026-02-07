<div align="center">
  <br />
    <a href="https://github.com/iamvikaspatel/StockMe" target="_blank">
      <img src="public/readme/hero.webp" alt="StockMe - Stock Market Tracker">
    </a>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-Next.js_15-black?style=for-the-badge&logoColor=white&logo=next.js&color=000000"/>
    <img src="https://img.shields.io/badge/-Better_Auth-black?style=for-the-badge&logoColor=white&logo=betterauth&color=7C3AED"/>
    <img src="https://img.shields.io/badge/-Shadcn_UI-black?style=for-the-badge&logoColor=white&logo=shadcnui&color=000000"/>
    <img src="https://img.shields.io/badge/-Inngest-black?style=for-the-badge&logoColor=white&logo=inngest&color=6366F1"/><br/>
    <img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=47A248"/>
    <img src="https://img.shields.io/badge/-TailwindCSS_4-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4"/>
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6"/>
    <img src="https://img.shields.io/badge/-Finnhub_API-black?style=for-the-badge&logoColor=white&logo=finnhub&color=EF4444"/>
  </div>

  <h1 align="center">📈 StockMe - AI-Powered Stock Market Tracker</h1>
  
  <p align="center">
    <strong>Real-time stock tracking, intelligent alerts, and AI-driven market insights</strong>
  </p>

  <p align="center">
    <a href="#introduction">Introduction</a> •
    <a href="#features">Features</a> •
    <a href="#tech-stack">Tech Stack</a> •
    <a href="#quick-start">Quick Start</a> •
    <a href="#project-structure">Project Structure</a>
  </p>
  
</div>

---

## <a name="introduction">✨ Introduction</a>

**StockMe** is a modern, full-stack stock market tracking application that empowers users to monitor financial markets in real-time with intelligent automation. Built with cutting-edge technologies like **Next.js 15**, **MongoDB**, **Better Auth**, and **Inngest**, StockMe delivers a seamless experience for tracking stocks, managing watchlists, and receiving personalized alerts.

### 🎯 What Makes StockMe Special?

- **Real-Time Market Data**: Integration with Finnhub API provides live stock prices, historical charts, and company financials
- **Event-Driven Architecture**: Powered by Inngest for automated workflows, background jobs, and scheduled tasks
- **AI-Powered Insights**: Leverage Google Gemini API for intelligent market summaries, sentiment analysis, and earnings reports
- **Secure Authentication**: Built-in email/password login with Better Auth framework
- **Email Notifications**: Automated alerts via Nodemailer when stocks hit your target prices
- **Interactive Charts**: TradingView widgets for both line charts and candlestick patterns
- **Responsive Design**: Beautiful UI built with Shadcn components and TailwindCSS 4

Whether you're a developer learning full-stack development, a trader needing market insights, or an investor tracking your portfolio, StockMe provides the tools you need in a clean, intuitive interface
4. 🤸 [Quick Start](#quick-start)
5. 🔗 [Assets](#links)
6. 🚀 [More](#more)



## <a name="introduction">✨ Introduction</a>

AI-powered modern stock market app built with Next.js, Shadcn, Better Auth, and Inngest! Track real-time prices, set personalized alerts, explore company insights, and manage watchlists. The admin dashboard allows managing stocks, publishing news, and monitoring user activity, while event-driven workflows power automated alerts, AI-driven daily digests, earnings notifications, and sentiment analysis—perfect for devs who want a dynamic, real-time financial platform.



## <a name="tech-stack">⚙️ Tech Stack</a>

- **[Better Auth](https://www.better-auth.com/)** is a framework-agnostic authentication and authorization library for TypeScript. It provides built-in support for email/password login, social sign-on (Google, GitHub, Apple, and more), and multi-factor authentication, simplifying user authentication and account management.

- **[CodeRabbit](https://jsm.dev/stocks-coderabbit)** is an AI-powered code review assistant that integrates with GitHub. It helps developers catch bugs, enforce best practices, and maintain consistent code quality across pull requests, reducing manual review effort and speeding up the development workflow.


- **[Finnhub](https://finnhub.io/)** is a real-time financial data API that provides stock, forex, and cryptocurrency market data. It offers developers access to fundamental data, economic indicators, and news, making it useful for building trading apps, dashboards, and financial analysis tools.

- **[Inngest](https://jsm.dev/stocks-inngest)** is a platform for event-driven workflows and background jobs. It allows developers to build reliable, scalable automated processes such as real-time alerts, notifications, and AI-powered workflows.

- **[MongoDB](https://www.mongodb.com/)** is a flexible, high-performance NoSQL database. It stores data in JSON-like documents, supports dynamic schemas, and provides robust features for scalability, replication, and querying.

- **[Nodemailer](https://nodemailer.com/)** is a Node.js library for sending emails easily. It supports various transport methods such as SMTP, OAuth2, and third-party services, making it a reliable tool for handling transactional emails, notifications, and contact forms in applications.

- **[Next.js](https://nextjs.org/docs)** is a powerful React framework for building full-stack web applications. It provides server-side rendering, static site generation, and API routes, allowing developers to create optimized and scalable apps quickly.

- **[Shadcn](https://ui.shadcn.com/docs)** is an open-source library of fully customizable, accessible React components. It helps teams rapidly build consistent, visually appealing UIs while allowing full control over design and layout.

- **[TailwindCSS](https://tailwindcss.com/)** is a utility-first CSS framework that allows developers to build custom, responsive designs quickly without leaving their HTML. It provides pre-defined classes for layout, typography, colors, and more.

- **[TypeScript](https://www.typescriptlang.org/)** is a statically typed superset of JavaScript that improves code quality, tooling, and error detection. It is ideal for building large-scale applications and enhances maintainability.
### 📊 Core Functionality

- **Real-Time Stock Dashboard**
  - Live price updates from Finnhub API
  - Interactive TradingView charts (line & candlestick)
  - Historical price data and performance metrics
  - Company profile, market cap, and key statistics

- **Smart Search & Discovery**
  - Fast command palette (⌘K) for instant stock search
  - Search by symbol, company name, or industry
  - Recently viewed stocks history
  - Trending stocks section

- **Personalized Watchlist**
  - Add/remove stocks with one click
  - Track multiple stocks simultaneously
  - Quick access from header navigation
  - Persistent storage in MongoDB

- **Intelligent Alerts System**
  - Set price alerts (above/below thresholds)
  - Volume spike notifications
  - Email alerts via Nodemailer
  - Customizable alert preferences

### 🤖 AI & Automation

- **AI-Powered Market Insights**
  - Daily market summaries generated by Google Gemini
  - Earnings report analysis
  - Sentiment analysis from news & filings
  - Personalized stock recommendations
git@github.com:iamvikaspatel/StockMe.git
cd StockMengest)**
  - Automated price monitoring
  - Scheduled alert checks
  - Background job processing
  - Webhook integrations

### 🔐 Authentication & User Management

- **Secure Authentication with Better Auth**
  - Email/password registration and login
  - Session management
  - Password recovery
  - Protected routes and API endpoints
.local` in the root of your project and add the following content:

```env
NODE_ENV='development'
NEXT_PUBLIC_BASE_URL=http://localhost:3000

# FINNHUB - Stock Market Data API
# Get your free API key: https://finnhub.io
NEXT_PUBLIC_FINNHUB_API_KEY=your_finnhub_api_key
FINNHUB_BASE_URL=https://finnhub.io/api/v1

# MONGODB - Database
# Get your connection string: https://www.mongodb.com/products/platform/atlas-database
MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/stockme

# BETTER AUTH - Authentication
# Generate a secure secret: openssl rand -base64 32
BETTER_AUTH_SECRET=your_secure_secret_key_here
BETTER_AUTH_URL=http://localhost:3000

# GEMINI - AI API for market insights
# Get your API key: https://aistudio.google.com/app/apikey
GEMINI_API_KEY=your_gemini_api_key

# NODEMAILER - Email notifications
# Use Gmail App Password or SMTP credentials
NODEMAILER_EMAIL=your-email@gmail.com
NODEMAILER_PASSWORD=your_app_password

Start the development server:

```bash
npm run dev
```

In a separate terminal, start Inngest Dev Server for event-driven workflows:
---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to StockMe:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- [Finnhub](https://finnhub.io/) for providing free stock market data API
- [Inngest](https://www.inngest.com/) for event-driven workflow platform
- [Better Auth](https://www.better-auth.com/) for authentication framework
- [Shadcn UI](https://ui.shadcn.com/) for beautiful, accessible components
- [TradingView](https://www.tradingview.com/) for interactive chart widgets

---

## 📧 Contact

**Vikas Patel** - [patelvikas276@gmail.com](mailto:patelvikas276@gmail.com)

Project Link: [https://github.com/iamvikaspatel/StockMe](https://github.com/iamvikaspatel/StockMe)

---

<div align="center">
  <p>Built with ❤️ by <a href="https://github.com/iamvikaspatel">Vikas Patel</a></p>
  <p>⭐ Star this repo if you find it helpful!</p>
</div

## <a name="project-structure">📁 Project Structure</a>

```
StockMe/
├── app/                          # Next.js App Router
│   ├── (auth)/                  # Authentication routes
│   │   ├── sign-in/            # Login page
│   │   └── sign-up/            # Registration page
│   ├── (root)/                  # Main application routes
│   │   ├── page.tsx            # Dashboard/Home page
│   │   └── stocks/[symbol]/    # Dynamic stock detail page
│   ├── api/                     # API routes
│   │   └── inngest/            # Inngest webhook endpoint
│   └── layout.tsx               # Root layout
│
├── components/                   # React Components
│   ├── ui/                      # Shadcn UI components
│   ├── forms/                   # Form components
│   ├── Header.tsx               # Navigation header
│   ├── SearchCommand.tsx        # Search command palette
│   ├── TradingViewWidget.tsx    # Stock chart widget
│   └── WatchlistButton.tsx      # Add to watchlist button
│
├── lib/                          # Core logic & utilities
│   ├── actions/                 # Server actions
│   │   ├── auth.actions.ts     # Authentication logic
│   │   ├── finnhub.actions.ts  # Stock data fetching
│   │   ├── user.actions.ts     # User management
│   │   └── watchlist.actions.ts # Watchlist operations
│   ├── better-auth/             # Auth configuration
│   ├── inngest/                 # Event-driven workflows
│   │   ├── client.ts           # Inngest client setup
│   │   ├── functions.ts        # Background jobs
│   │   └── prompts.ts          # AI prompt templates
│   └── nodemailer/              # Email service
│
├── database/                     # Database layer
│   ├── models/                  # Mongoose schemas
│   └── mongoose.ts              # Database connection
│
├── hooks/                        # Custom React hooks
│   ├── useDebounce.ts           # Debounce hook
│   └── useTradingViewWidget.tsx # Chart widget hook
│
├── middleware/                   # Next.js middleware
│   └── index.ts                 # Route protection
│
├── types/                        # TypeScript definitions
│   └── global.d.ts              # Global type declarations
│
└── public/                       # Static assets
    └── assets/                  # Images, icons, logos
```

---

## <a name="architecture">🏗️ Architecture & Key Concepts</a>

### Tech Stack Overview

| Technology | Purpose | Why Used |
|------------|---------|----------|
| **Next.js 15** | Frontend Framework | Server-side rendering, API routes, app router |
| **TypeScript** | Language | Type safety, better DX, fewer bugs |
| **MongoDB + Mongoose** | Database | Flexible schema for user data & watchlists |
| **Better Auth** | Authentication | Secure, framework-agnostic auth solution |
| **Inngest** | Background Jobs | Event-driven workflows, scheduled tasks |
| **Finnhub API** | Stock Data | Real-time market data, company info |
| **Google Gemini** | AI Insights | Generate market summaries & analysis |
| **Nodemailer** | Email Service | Send alert notifications to users |
| **Shadcn UI** | UI Components | Accessible, customizable React components |
| **TailwindCSS 4** | Styling | Utility-first CSS, rapid development |

### Key Features Implementation

#### 1. Real-Time Stock Data
- Finnhub API integration via server actions
- Cached responses for performance
- Error handling and fallbacks

#### 2. Event-Driven Workflows (Inngest)
```typescript
// Background jobs for alerts, AI summaries, etc.
inngest.createFunction(
  { id: "check-price-alerts" },
  { cron: "*/5 * * * *" }, // Every 5 minutes
  async ({ step }) => {
    // Check user alerts and send notifications
  }
);
```

#### 3. Authentication Flow
- Better Auth handles sessions and security
- Protected routes via middleware
- Server-side session validation

#### 4. AI-Powered Insights
- Google Gemini API generates market summaries
- Custom prompts for different use cases
- Automated daily digest emails
### 🔑 Getting Your API Keys:

1. **Finnhub**: Sign up at [finnhub.io](https://finnhub.io) → Get free API key
2. **MongoDB**: Create cluster at [MongoDB Atlas](https://www.mongodb.com/products/platform/atlas-database) → Get connection string
3. **Gemini**: Visit [Google AI Studio](https://aistudio.google.com/app/apikey) → Generate API key
4. **Nodemailer**: For Gmail, enable [2FA](https://myaccount.google.com/security) → Generate [App Password](https://myaccount.google.com/apppasswords)
5. **Inngest**: Sign up at [inngest.com](https://www.inngest.com) → Get event and signing keys

⚠️ **Important**: Never commit your `.env.local` file to version control!
Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/adrianhajdin/signalist_stock-tracker-app.git
cd signalist_stock-tracker-app
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
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

#NODEMAILER
NODEMAILER_EMAIL=
NODEMAILER_PASSWORD=
```

Replace the placeholder values with your real credentials. You can get these by signing up at: [**MongoDB**](https://www.mongodb.com/products/platform/atlas-database), [**Gemini**](https://aistudio.google.com/prompts/new_chat?utm_source=chatgpt.com), [**Inngest**](https://jsm.dev/stocks-inggest), [**Finnhub**](https://finnhub.io).

**Running the Project**

```bash
npm run dev
npx inngest-cli@latest dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## <a name="links">🔗 Assets</a>

Assets and snippets used in the project can be found in the **[video kit](https://jsm.dev/stocks-kit)**.

<a href="https://jsm.dev/stocks-kit" target="_blank">
  <img src="public/readme/videokit.webp" alt="Video Kit Banner">
</a>

## <a name="more">🚀 More</a>

**Advance your skills with Next.js Pro Course**

Enjoyed creating this project? Dive deeper into our PRO courses for a richer learning adventure. They're packed with
detailed explanations, cool features, and exercises to boost your skills. Give it a go!

<a href="https://jsm.dev/stocks-jsmpro" target="_blank">
  <img src="public/readme/jsmpro.webp" alt="Project Banner">
</a>
