AI SaaS Platform

An AI-driven financial SaaS platform that provides real-time insights, portfolio analysis, and investment recommendations through a clean, scalable, and secure web application.

📌 Features

🔍 AI-Powered Insights: Get real-time market analysis and personalized financial advice.

📊 Interactive Dashboards: Dynamic data visualization with smooth state handling.

🔐 Secure Authentication: Powered by Clerk
 for seamless login.

⚡ Next.js + Tailwind UI: Responsive, high-performance frontend.

📡 Supabase Integration: Scalable backend with data persistence.

🔑 API Key Management: Gemini and ArcJet integrations for AI services.

🔄 Reusable UI Components: Built with Shadcn UI and Tailwind for rapid scaling.

🛠️ Tech Stack
Layer	Technology
Frontend	Next.js, React, Tailwind CSS, Shadcn UI
Backend	Supabase, Prisma ORM
AI/ML Services	Google Gemini API, ArcJet
Authentication	Clerk
Hosting/Deployment	Vercel, Supabase

📂 Project Structure
ai-finance-platform/
├── actions/         # Server-side actions and API calls
├── app/             # Next.js App Router pages and layouts
├── components/      # Reusable UI components
├── data/            # Static or mock data files
├── emails/          # Email templates and notification logic
├── hooks/           # Custom React hooks
├── lib/             # Utility functions, helpers, configs
├── prisma/          # Prisma schema and migrations
├── public/          # Static assets
├── middleware.js    # Middleware for auth, routing, etc.
├── next.config.mjs  # Next.js configuration
├── tailwind.config.js # Tailwind styling config
└── README.md        # Project documentation

🔧 Getting Started
1. Clone the Repository
git clone https://github.com/Saptarshi04/AI-SaaS-Platform.git
cd ai-finance-platform

2. Install Dependencies
npm install

3. Set Up Environment Variables

Create a .env.local file and add the following:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key
CLERK_SECRET_KEY=your_key
NEXT_PUBLIC_SUPABASE_URL=your_url
SUPABASE_SERVICE_ROLE_KEY=your_key
GEMINI_API_KEY=your_key
ARCJET_KEY=your_key

4. Run the App
npm run dev


Visit: http://localhost:3000

🔥 Key Highlights

Modular UI: Shadcn + Tailwind ensures clean design and scalability.

AI Integration: Google Gemini for insights and recommendations.

Real-Time Data: Supabase for live financial data and user portfolio tracking.

Security: Environment-variable-driven secrets management.

📜 Roadmap

 Advanced AI-based portfolio optimization

 Multi-user organization workspaces

 Mobile-first enhancements

 Integration with brokerage APIs

🤝 Contributing

Contributions are welcome! Please fork the repo, create a branch, and submit a PR.

📄 License

MIT License © 2025 [Saptarshi Paik]
