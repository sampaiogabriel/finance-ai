# 💰 FinanceAI

This repository contains **FinanceAI**, a project developed during the Full Stack Week. The goal is to provide a financial platform powered by Artificial Intelligence to help users manage their personal finances.

## 🚀 Tech Stack

- **React** – JavaScript library for building user interfaces  
- **Next.js 13** – React framework offering server-side rendering and static site generation  
- **NextAuth.js** – Authentication library with OAuth support  
- **PostgreSQL** – Relational database management system  
- **Prisma** – ORM for Node.js and TypeScript for database access  
- **shadcn/ui** – Reusable and styled UI component library  
- **Tailwind CSS** – Utility-first CSS framework for fast and consistent styling  
- **Stripe API** – Online payment platform for secure transaction processing  

## 📌 Features

- **Financial Dashboard** – View and manage your finances with an intuitive dashboard  
- **Expense Analytics** – Gain insights into your spending habits and identify saving opportunities  
- **AI-Powered Financial Forecasting** – Receive personalized predictions based on your financial behavior  
- **Secure Authentication** – Robust login and registration system to protect your information  
- **Payments Integration** – Manage transactions with integrated Stripe API support  

## 🛠️ Getting Started

1. **Clone the repository**:

   ```bash
   git clone https://github.com/sampaiogabriel/finance.ai.git
   ```

2. **Install dependencies**:

   ```bash
   cd fullstackweek-financeai
   npm install
   ```

3. **Set environment variables**:

   Create a `.env` file in the project root and add the following variables:

   ```env
   DATABASE_URL=your_database_url
   NEXTAUTH_URL=your_auth_url
   STRIPE_API_KEY=your_stripe_api_key
   ```

4. **Run database migrations**:

   ```bash
   npx prisma migrate dev
   ```

5. **Start the development server**:

   ```bash
   npm run dev
   ```

   The app will be available at `http://localhost:3000`.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues and pull requests. Before contributing, please read the `CONTRIBUTING.md` file to understand the project's guidelines.

## 📝 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.
