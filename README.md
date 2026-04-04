# 📧 AI Email Classifier

![Next.js](https://img.shields.io/badge/Next.js-14-black.svg?style=flat&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-18-blue.svg?style=flat&logo=react&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC.svg?style=flat&logo=tailwind-css&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-API-412991.svg?style=flat&logo=openai&logoColor=white)
![Gemini AI](https://img.shields.io/badge/Gemini-AI-FFD700.svg?style=flat)
![Google APIs](https://img.shields.io/badge/Google_APIs-Integration-4285F4.svg?style=flat&logo=google)

An intelligent, full-stack application built with **Next.js** that automatically categorizes and organizes your emails using advanced language models (LLMs). By leveraging the power of **OpenAI** and **Google Gemini AI**, along with deep integration into the **Gmail API**, this application acts as your smart inbox assistant.

## ✨ Features

- **🔒 Secure Authentication:** OAuth 2.0 integration via `next-auth` for seamless and secure sign-in using your Google Account.
- **📩 Direct Inbox Sync:** Seamlessly fetches your emails using `googleapis` (Gmail API).
- **🧠 AI-Powered Classification:** Utilizes OpenAI's GPT models and Google's Gemini AI (`@google/generative-ai`) to intelligently categorize emails (e.g., Important, Spam, Newsletter, Work, Personal).
- **⚡ Lightning Fast UI:** Responsive, modern frontend crafted with **React 18** and **Tailwind CSS**.
- **🛠️ Robust Architecture:** Full-stack React framework utilizing **Next.js 14** Server Components and API Routes.

## 🏗️ Technical Stack

- **Frontend:** Next.js 14, React 18, Tailwind CSS, Autoprefixer
- **Backend (API):** Next.js API Routes, Node.js
- **Authentication:** NextAuth.js (Google Provider)
- **AI Integrations:** `openai` platform, `@google/generative-ai`
- **External APIs:** `googleapis` (for Gmail access)
- **Styling:** PostCSS, Tailwind CSS

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed to run this application locally:
- **Node.js** (v18.0.0 or higher recommended)
- **npm**, **yarn**, **pnpm**, or **bun**

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/AdityaRanjan-012/AI_Email_Classifier.git
   cd AI_Email_Classifier
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Configuration**
   Create a `.env.local` file in the root of the project and add the necessary secret keys (e.g., Google OAuth Credentials, OpenAI API Key, Gemini API Key).
   ```env
   # Next Auth
   NEXTAUTH_URL=http://localhost:3000
   NEXTAUTH_SECRET=your_nextauth_secret

   # Google API (Gmail & OAuth)
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret

   # AI API Keys
   OPENAI_API_KEY=your_openai_api_key
   GEMINI_API_KEY=your_gemini_api_key
   ```

4. **Run the Development Server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🤝 Contributing

Contributions are always welcome! Feel free to open an issue or submit a pull request if you have ideas for improving the classifier, adding new AI models, or enhancing the UI.

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
