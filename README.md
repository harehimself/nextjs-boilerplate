
<p align="center">
   <img src="https://raw.githubusercontent.com/harehimself/nextjs-boilerplate/main/nextjs-boilerplate.png">
</p>

<p align="center">
   Production-ready Next.js boilerplate with modern development tools and best practices. Features TypeScript, Tailwind CSS, authentication, database integration, and deployment configurations. Designed for rapid application development with enterprise-grade architecture. Includes testing frameworks, CI/CD pipelines, and performance optimizations. Perfect for building scalable web applications with minimal setup time.
</p>
<br>
<p align="center">
  <a href="https://github.com/harehimself/nextjs-boilerplate/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/harehimself/nextjs-boilerplate" alt="Contributors"></a>
  <a href="https://github.com/harehimself/nextjs-boilerplate/network/members">
    <img src="https://img.shields.io/github/forks/harehimself/nextjs-boilerplate" alt="Forks"></a>
  <a href="https://github.com/harehimself/nextjs-boilerplate/stargazers">
    <img src="https://img.shields.io/github/stars/harehimself/nextjs-boilerplate" alt="Stars"></a>
  <a href="https://github.com/harehimself/nextjs-boilerplate/issues">
    <img src="https://img.shields.io/github/issues/harehimself/nextjs-boilerplate" alt="Issues"></a>
  <a href="https://github.com/harehimself/nextjs-boilerplate/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/harehimself/nextjs-boilerplate" alt="MIT License"></a>
</p>

---

## Table of Contents
  - [NextJS Boilerplate](#nextjs-boilerplate)
  - [Features](#features)
  - [Installation](#installation)
  - [Quick Start](#quick-start)
  - [Tech Stack](#tech-stack)
  - [Project Structure](#project-structure)
  - [Benefits](#benefits)
  - [How It Compares](#how-it-compares)
  - [License](#license)

<br>

## NextJS Boilerplate
A comprehensive, production-ready Next.js boilerplate that accelerates web application development with modern tooling, best practices, and enterprise-grade architecture.

<br>

## Features
- ✅ Next.js 14+ with App Router
- ✅ Tailwind CSS with custom design system
- ✅ Authentication (NextAuth.js)
- ✅ Database integration (Prisma + PostgreSQL)
- ✅ Responsive design and mobile-first approach
- ✅ Testing suite (Jest + Testing Library)
- ✅ CI/CD pipeline configurations
- ✅ Performance monitoring and analytics

<br>

## Installation
1. Clone the repository:
```bash
git clone https://github.com/harehimself/nextjs-boilerplate.git
cd nextjs-boilerplate
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Configure environment variables:
```bash
cp .env.example .env.local
# Edit .env.local with your configuration
```

4. Set up the database:
```bash
npx prisma migrate dev
npx prisma generate
```

<br>

## Quick Start
1. Start the development server:
```bash
npm run dev
# or
yarn dev
```

2. Open [http://localhost:3000](http://localhost:3000) in your browser

3. Start building your application:
   - Modify `app/page.tsx` for the homepage
   - Add new routes in the `app/` directory
   - Customize components in `components/`
   - Update styling in `styles/`

<br>

## Tech Stack
- **Framework**: Next.js 14+ (App Router)
- **Styling**: Tailwind CSS + shadcn/ui components
- **Authentication**: NextAuth.js
- **Database**: Prisma ORM + PostgreSQL
- **Testing**: Jest + React Testing Library
- **Deployment**: Vercel-optimized
- **Code Quality**: ESLint + Prettier + Husky
- **Type Safety**: TypeScript

<br>

## Project Structure
- `app/`: Next.js 14 app directory structure
- `components/`: Reusable UI components
- `lib/`: Utility functions and configurations
- `prisma/`: Database schema and migrations
- `public/`: Static assets
- `styles/`: Global styles and Tailwind config
- `tests/`: Test files and utilities
- `types/`: TypeScript type definitions

<br>

## Benefits
- Eliminates hours of initial setup and configuration
- Production-ready architecture with proven patterns
- Built-in security best practices and performance optimizations
- Comprehensive testing framework for reliable development
- Scalable file structure that grows with your application
- Modern development experience with hot reloading and TypeScript

<br>

## How It Compares
- More comprehensive than basic Next.js starters
- Includes authentication and database setup out of the box
- Production-ready with CI/CD and deployment configurations
- Follows current Next.js best practices and conventions
- Optimized for both developer experience and application performance

<br>

## License
MIT License © 2025 [HareLabs](https://github.com/harehimself)
