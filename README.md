# ProLingo

ProLingo is a SaaS-based platform designed to help users learn programming languages in an interactive and gamified way, similar to how Duolingo teaches spoken languages.

## 🚀 Features
- **Interactive Quizzes**: Engaging challenges to test and reinforce learning.
- **Gamification**: Progress tracking, hearts system, and rewards.
- **User Authentication**: Secure sign-in with Firebase authentication.
- **Subscription Model**: Integrated with Stripe for premium features.
- **Responsive UI**: Built with modern design principles for a seamless experience.
- **Progress Tracking**: Save and resume learning with personalized progress.

## 🛠️ Tech Stack
- **Frontend**: Next.js 14, React, Tailwind CSS, ShadCN UI
- **Backend**: Server Actions, Drizzle ORM, PostgreSQL
- **Authentication**: Clerk Auth
- **Payments**: Stripe

## 📦 Installation
### Prerequisites
- Node.js (>= 18)
- PostgreSQL Database
- Clerk Project with Authentication enabled
- Stripe Account for payments

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Harshvardhan-18/E-Commit-Prolingo.git
   cd prolingo
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   Create a `.env.local` file and add the following:
   ```env
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_next_clerk_key
    CLERK_SECRET_KEY=your_clerk_key
    NEXT_PUBLIC_CLERK_SIGN_IN_FORCE_REDIRECT_URL=/demo
    NEXT_PUBLIC_CLERK_SIGN_UP_FORCE_REDIRECT_URL=/demo
    DATABASE_URL=your_pg_url
    STRIPE_SECRET_KEY=your_stripe_secret_key
   ```
4. Run database migrations:
   ```bash
   npx drizzle-kit push
   ```
5. Start the development server:
   ```bash
   npm run dev
   ```

## 🚧 Development
### Running in Development Mode
```bash
npm run dev
```
### Building for Production
```bash
npm run build
```

## 🤝 Contributing
We welcome contributions! Feel free to open issues and pull requests.

