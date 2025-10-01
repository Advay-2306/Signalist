<div align="center">
    <h1 align="center">Signalist -- Stock Market Tracker Application</h1>
  <br />

  <div>
    <img src="https://img.shields.io/badge/-Next.js-black?style=for-the-badge&logoColor=white&logo=next.js&color=black"/>
    <img src="https://img.shields.io/badge/-Better Auth-black?style=for-the-badge&logoColor=white&logo=betterauth&color=black"/>
<img src="https://img.shields.io/badge/-Shadcn-black?style=for-the-badge&logoColor=white&logo=shadcnui&color=black"/>
<img src="https://img.shields.io/badge/-Inngest-black?style=for-the-badge&logoColor=white&logo=inngest&color=black"/><br/>

<img src="https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=00A35C"/>
<img src="https://img.shields.io/badge/-CodeRabbit-black?style=for-the-badge&logoColor=white&logo=coderabbit&color=9146FF"/>
<img src="https://img.shields.io/badge/-TailwindCSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=38B2AC"/>
<img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6"/>

  </div>

</div>

## 📋 <a name="table">Table of Contents</a>

1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)

## <a name="introduction">✨ Introduction</a>

AI-driven stock market platform built with Next.js, Shadcn, Better Auth, and Inngest. Track live prices, set custom alerts, and explore company insights. The admin dashboard enables stock management, news publishing, and user monitoring, while event-driven workflows power automated alerts, AI-generated daily summaries, and sentiment analysis—designed for developers building dynamic, real-time financial applications. Below are various technolgies I have utilized in building this project.

## <a name="tech-stack">⚙️ Tech Stack</a>

- **[Better Auth](https://www.better-auth.com/)** is a framework-agnostic authentication and authorization library for TypeScript. It provides built-in support for email/password login, social sign-on (Google, GitHub, Apple, and more), and multi-factor authentication, simplifying user authentication and account management.

- **[CodeRabbit](https://www.coderabbit.ai/)** is an AI-powered code review assistant that integrates with GitHub. It helps developers catch bugs, enforce best practices, and maintain consistent code quality across pull requests, reducing manual review effort and speeding up the development workflow.

- **[Finnhub](https://finnhub.io/)** is a real-time financial data API that provides stock, forex, and cryptocurrency market data. It offers developers access to fundamental data, economic indicators, and news, making it useful for building trading apps, dashboards, and financial analysis tools.

- **[Inngest](https://www.inngest.com/)** is a platform for event-driven workflows and background jobs. It allows developers to build reliable, scalable automated processes such as real-time alerts, notifications, and AI-powered workflows.

- **[MongoDB](https://www.mongodb.com/)** is a flexible, high-performance NoSQL database. It stores data in JSON-like documents, supports dynamic schemas, and provides robust features for scalability, replication, and querying.

- **[Nodemailer](https://nodemailer.com/)** is a Node.js library for sending emails easily. It supports various transport methods such as SMTP, OAuth2, and third-party services, making it a reliable tool for handling transactional emails, notifications, and contact forms in applications.

- **[Next.js](https://nextjs.org/docs)** is a powerful React framework for building full-stack web applications. It provides server-side rendering, static site generation, and API routes, allowing developers to create optimized and scalable apps quickly.

- **[Shadcn](https://ui.shadcn.com/docs)** is an open-source library of fully customizable, accessible React components. It helps teams rapidly build consistent, visually appealing UIs while allowing full control over design and layout.

- **[TailwindCSS](https://tailwindcss.com/)** is a utility-first CSS framework that allows developers to build custom, responsive designs quickly without leaving their HTML. It provides pre-defined classes for layout, typography, colors, and more.

- **[TypeScript](https://www.typescriptlang.org/)** is a statically typed superset of JavaScript that improves code quality, tooling, and error detection. It is ideal for building large-scale applications and enhances maintainability.

## <a name="features">🔋 Features</a>

1. **Stock Dashboard**: Monitor live stock prices with interactive line and candlestick charts, view historical trends, and filter by industry, performance, or market cap.

2. **Smart Search**: Quickly locate stocks using an intuitive search system built to streamline navigation across Signalist.

3. **Company Insights**: Access key financial metrics like PE ratio, EPS, revenue, news, filings, analyst ratings, and sentiment scores to support better decisions.

4. **Event-Driven Workflows**: Using **Inngest**, automate updates, schedule alerts, generate reports, and deliver AI-powered insights in real time.

5. **AI Summaries & Alerts**: Receive tailored market digests, daily summaries, and earnings notifications to stay on top of market movements.

6. **Analytics & Trends**: Analyze user behavior, stock activity, and engagement data to guide smarter trading and business strategies.

7. **Clean Architecture**: Designed with reusable, modular components to support scalability and maintainability.


**Cloning the Repository**

```bash
git clone https://github.com/Advay-2306/Signalist.git
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

**Running the Project**

```bash
npm run dev
npx inngest-cli@latest dev
```
