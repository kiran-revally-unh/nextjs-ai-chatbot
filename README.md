Kiran's Next.js AI Chatbot

🚀 Live Demo: kiran-nextjs-ai-chatbot.vercel.app

📌 Overview

Kiran's Next.js AI Chatbot is an open-source AI chatbot template built with Next.js 14, Vercel’s AI SDK, and OpenAI's GPT-4o. It supports multiple AI models, user authentication, and chat history storage. This project is fully customizable and scalable, making it a great starting point for AI-powered applications.

🎯 Features

Next.js 14 & App Router 🚀

Fast, optimized routing

React Server Components (RSCs) and Server Actions

AI SDK by Vercel 🧠

Supports OpenAI (GPT-4o), Anthropic, Cohere, and more

Hooks for building chat and generative UI

Modern UI with Tailwind CSS & ShadCN 🎨

Styled with Tailwind CSS

Uses ShadCN & Radix UI for components

Persistent Chat History & File Storage 📂

Vercel Postgres for saving chat history

Vercel Blob Storage for managing uploads

Secure Authentication with NextAuth.js 🔐

OAuth support (Google, GitHub, etc.)

Session management for users

🚀 Deployment

1-Click Deploy on Vercel

Deploy your own version instantly:



🛠️ Installation & Local Development

1️⃣ Clone the repository

git clone https://github.com/yourusername/kiran-nextjs-ai-chatbot.git
cd kiran-nextjs-ai-chatbot

2️⃣ Install dependencies

pnpm install

3️⃣ Set up environment variables

cp .env.example .env

Edit the .env file and add your OpenAI API Key and Auth Secret.

4️⃣ Run the development server

pnpm dev

Your chatbot will now be live at localhost:3000 🚀

📡 Backend API Configuration

Ensure your backend API URL is correct in your .env:

VITE_BACKEND_URL=http://localhost:5003

For production:

VITE_BACKEND_URL=https://your-backend-api.vercel.app

🏗️ Technologies Used

Next.js 14 (App Router, RSCs, Server Actions)

Vercel AI SDK (Supports multiple AI models)

OpenAI GPT-4o (Default AI model)

NextAuth.js (Secure authentication)

Vercel Postgres & Blob Storage (Persistent data storage)

Tailwind CSS & ShadCN (Modern UI styling)

TypeScript & pnpm (For better scalability)

🎉 Try it Live!

kiran-nextjs-ai-chatbot.vercel.app

This AI chatbot is ready for production and fully customizable! 🚀🔥

💡 Contributions & Feedback Welcome! If you have ideas or improvements, feel free to open an issue or contribute. 😊

