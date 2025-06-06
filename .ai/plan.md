# Teacher Platform - Project Planning

## 🎯 Vision
Ultimate all-in-one hub for teachers, students, and parents with AI-powered lesson planning, assessment tools, and seamless communication.

## 🏗️ Core Architecture
- **Frontend**: Next.js with TypeScript + Tailwind CSS
- **Backend**: Next.js API Routes + Supabase (Database + Auth + Real-time + Vector Store)
- **AI Services**: OpenRouter + LangChain.js for multi-agent workflows
- **Agent Framework**: LangChain.js for curriculum scraping, lesson generation, validation
- **Vector Database**: Supabase pgvector for curriculum documentation RAG
- **State Management**: React Context + Custom Hooks + SWR

## 👥 User Roles & Permissions
- **Teachers**: Full platform access, student management, content creation
- **Students**: Assignment submission, grade viewing, communication
- **Parents**: Child progress monitoring, teacher communication (read-only)

## 🎨 Design Principles
- Mobile-first responsive design
- Accessible (WCAG 2.1 AA compliance)
- Clean, intuitive teacher-focused UI
- Fast loading with optimistic updates

## 🔧 Technical Constraints
- Files under 500 lines max
- Component-based architecture
- Real-time updates for notifications
- Offline-capable for basic features

## 📋 Initial Implementation Priority Order
1.  **Authentication & Three-Role System** - Teacher/Student/Parent with proper relationships
2.  **Database Schema & RLS Policies** - Secure data access based on user roles
3.  **Curriculum Scraper Agent** - Foundation for all educational content
4.  **Teacher Dashboard** - Primary user workflow and lesson management
5.  **Lesson Plan Generator Agent** - Core AI value proposition with RAG
6.  **Student Portal** - Assignment submission and grade viewing
7.  **Parent Dashboard** - Child progress monitoring and teacher communication
8.  **Real-time Communication** - Messages, notifications, updates
9.  **Assessment & Grading Tools** - Automated grading and rubric generation
10. **Analytics & Reporting** - Progress tracking and performance insights 