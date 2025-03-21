# Javed Jabbar's Portfolio

A modern portfolio website built with Next.js 15, featuring AI chat integration and interactive animations.

## ✨ Features

- **AI-Powered Email Generation**: Create professional emails with AI assistance
- **Interactive Chat**: Talk directly with an AI version of me using advanced LLMs
- **Vector Embeddings**: Semantic search capabilities for more accurate AI responses
- **Dynamic Animations**: Engaging UI with smooth animations
- **Responsive Design**: Seamless experience across all devices
- **Dark Mode**: Eye-friendly interface for all lighting conditions
- **Project Showcase**: Interactive displays of my work and contributions


## 🛠️ Tech Stack

- **Frontend**: Next.js 15, TypeScript, Tailwind CSS, Framer Motion
- **AI Integration**: OpenRouter API (Llama 3.3)
- **Backend**: Next.js API Routes, Node.js
- **Vector Database**: Pinecone for semantic search and embeddings
- **Embeddings**: Google Gemini for generating vector embeddings
- **Search Capability**: Tavily API for real-time information
- **Email Services**: Nodemailer, Abstract API for email validation
- **Deployment**: Vercel with Edge Functions


The vector store is configured in `lib/embeddings.ts` with the following settings:
- Dimension: 768 (Google Gemini embeddings)
- Metric: Cosine similarity
- Pod type: Starter (free tier)

You can modify these settings in the `initializeVectorStore` function if needed.
