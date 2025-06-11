# 🚀 Ultimate Quick Stack — Next.js Full-Stack Boilerplate for Scalable Web Apps

A production-ready boilerplate combining Next.js, Tailwind CSS, MongoDB (via Mongoose), Auth0 authentication, and Stripe payments. Built to accelerate time-to-market by applying modern best practices and maximizing extensibility.

---

## 🧰 Technology Stack

- **Next.js:** React framework for hybrid static and server rendering, optimized for production.
- **Tailwind CSS:** Utility-first CSS for fast, responsive UI development.
- **MongoDB & Mongoose:** Flexible NoSQL database with structured schema modeling.
- **Auth0:** Secure, scalable authentication and authorization.
- **Stripe:** Enterprise-grade payment processing and billing.

---

## ⚡️ Quick Start

Clone the repo and install dependencies:

```bash
git clone https://github.com/MuhammadTanveerAbbas/Scalable-Next.js-Boilerplate.git
cd Scalable-Next.js-Boilerplate
npm install
```

Set up your environment variables in `.env.local`:

```bash
# Auth0
AUTH0_SECRET=
AUTH0_ISSUER_BASE_URL=
AUTH0_CLIENT_ID=
AUTH0_CLIENT_SECRET=
AUTH0_REDIRECT_URI=

# MongoDB
MONGODB_URI=

# Stripe
STRIPE_SECRET_KEY=
STRIPE_PRICE=

# Frontend
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Start development server:

```bash
npm run dev  # or yarn dev / pnpm dev / bun dev
```

---

## 🎯 Why This Boilerplate?

- **End-to-end integration:** Fully connects frontend and backend for seamless data flow.
- **Security-first:** Implements OAuth via Auth0 for robust user authentication.
- **Scalable DB:** MongoDB + Mongoose schemas support complex data models.
- **Payment-ready:** Stripe integration enables subscriptions and payments out of the box.
- **Fast UI:** Tailwind CSS accelerates styling and responsive design.
- **Developer-centric:** Includes TypeScript and ESLint for better code quality and maintainability.

---

## 📝 License

MIT License — use freely in your projects.
