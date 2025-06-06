# 🎓 ALUA - Ultimate Teacher Platform

> **AI-Powered Educational Hub for Teachers, Students, and Parents**

[![Next.js](https://img.shields.io/badge/Next.js-14-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Supabase](https://img.shields.io/badge/Supabase-PostgreSQL-3ECF8E?style=flat-square&logo=supabase)](https://supabase.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)
[![LangChain](https://img.shields.io/badge/LangChain-AI-FF6B6B?style=flat-square)](https://langchain.com/)

## 🌟 Vision

ALUA is the **Ultimate Teacher Platform** - a comprehensive, AI-powered educational hub that revolutionizes how teachers create lessons, students learn, and parents stay engaged. Built for the modern classroom with cutting-edge AI agents and real-time collaboration.

## ✨ Key Features

### 🤖 AI-Powered Teaching Assistant
- **Curriculum Scraper Agent**: Automatically fetches and organizes state education standards
- **Lesson Plan Generator**: Creates grade-appropriate, curriculum-aligned lessons using RAG
- **Assessment Creator**: Generates quizzes, tests, and rubrics automatically
- **Grading Assistant**: Provides automated scoring and detailed feedback
- **Differentiation Agent**: Adapts content for diverse learning styles

### 👩‍🏫 For Teachers
- 📚 **Smart Lesson Planning** with AI assistance and curriculum compliance
- 📊 **Comprehensive Grade Book** with automated and manual entries
- 👥 **Class Management** with student progress tracking
- 📱 **Real-time Communication** with students and parents
- 📈 **Analytics Dashboard** for performance insights

### 👨‍🎓 For Students
- 📝 **Assignment Portal** with easy submission and feedback
- 🎯 **Grade Tracking** with detailed progress reports
- 📅 **Calendar Integration** for deadlines and events
- 💬 **Direct Teacher Communication**
- 📖 **Study Resources** and lesson access

### 👪 For Parents
- 👀 **Child Progress Monitoring** with real-time updates
- 📊 **Grade and Assignment Visibility** (read-only)
- 📞 **Teacher Communication** portal
- 📅 **School Calendar** and event notifications
- 📈 **Detailed Progress Reports**

## 🏗️ Tech Stack

### Frontend
- **Next.js 14** - React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **React Hook Form + Zod** - Form handling and validation

### Backend & Database
- **Supabase** - PostgreSQL database with real-time subscriptions
- **Row Level Security (RLS)** - Role-based data access
- **Supabase Auth** - Multi-role authentication system
- **pgvector** - Vector database for AI embeddings

### AI & Agents
- **LangChain.js** - AI agent framework
- **OpenRouter** - Multi-model LLM access
- **Retrieval-Augmented Generation (RAG)** - Curriculum-compliant content
- **Vector Embeddings** - Semantic search and content matching

### Infrastructure
- **Vercel** - Deployment and hosting
- **GitHub Actions** - CI/CD pipeline
- **Real-time Subscriptions** - Live updates and notifications

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn
- Git

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Chillbruhhh/alua.git
cd alua
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
```bash
cp .env.example .env.local
```

4. **Configure your `.env.local`**
```env
# Supabase
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key

# OpenRouter AI
OPENROUTER_API_KEY=your_openrouter_key

# Next.js
NEXTAUTH_SECRET=your_nextauth_secret
NEXTAUTH_URL=http://localhost:3000
```

5. **Run the development server**
```bash
npm run dev
```

6. **Open your browser**
Navigate to `http://localhost:3000`

## 🎯 Project Structure

```
alua/
├── .ai/                    # AI-driven development guidance
│   ├── guides/            # Coding standards and best practices
│   ├── backlog/           # Future features and tasks
│   ├── doing/             # Active development tasks
│   ├── done/              # Completed features
│   ├── task.md            # Main project roadmap
│   ├── plan.md            # Project vision and architecture
│   └── llms.txt           # AI assistant guidelines
├── src/
│   ├── app/               # Next.js App Router
│   ├── components/        # Reusable UI components
│   ├── hooks/             # Custom React hooks
│   ├── lib/               # Utility functions and configs
│   ├── types/             # TypeScript type definitions
│   └── agents/            # AI agent implementations
├── supabase/
│   ├── migrations/        # Database schema changes
│   └── seed.sql           # Initial data
└── docs/                  # Project documentation
```

## 🎨 Design Principles

- **Mobile-First**: Responsive design for all devices
- **Accessibility**: WCAG 2.1 AA compliance
- **Performance**: Optimized loading and real-time updates
- **Security**: Role-based access with RLS policies
- **Modularity**: Components under 500 lines, clean architecture

## 📋 Development Roadmap

### 🚀 Sprint 1: Foundation (Week 1)
- [x] Project setup and architecture
- [ ] Authentication system with role management
- [ ] Database schema with RLS policies
- [ ] Basic UI components and layouts

### 🚀 Sprint 2: AI Agents (Week 2)
- [ ] Curriculum scraper agent
- [ ] Lesson plan generator with RAG
- [ ] Teacher dashboard and tools
- [ ] Assessment creation system

### 🚀 Sprint 3: User Portals (Week 3)
- [ ] Student assignment portal
- [ ] Parent monitoring dashboard
- [ ] Real-time communication system
- [ ] Grade management interface

### 🚀 Sprint 4: Polish & Features (Week 4)
- [ ] Advanced analytics and reporting
- [ ] Mobile optimization
- [ ] Performance enhancements
- [ ] Hackathon presentation prep

## 🤝 Contributing

This project follows a structured development approach guided by AI-assisted planning:

1. **Check** `.ai/task.md` for current sprint priorities
2. **Follow** coding standards in `.ai/guides/`
3. **Update** task progress and discoveries
4. **Test** thoroughly before submitting

## 📄 License

MIT License - see [LICENSE](LICENSE) for details

## 🏆 Hackathon Goals

- **Primary**: Demonstrate AI-powered educational tools
- **Secondary**: Showcase real-time collaboration features
- **Tertiary**: Highlight accessibility and compliance features

## 📞 Contact

- **Developer**: [@Chillbruhhh](https://github.com/Chillbruhhh)
- **Project**: [alua](https://github.com/Chillbruhhh/alua)
- **Demo**: Coming soon! 🚀

---

<div align="center">
  <strong>Built with ❤️ for educators, students, and families</strong>
  <br>
  <em>Empowering education through AI innovation</em>
</div> 