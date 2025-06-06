# Database & Authentication Guidelines

## 🔐 Supabase Row-Level Security (RLS)
- **Strict Role-Based Access**: Implement RLS policies for all tables to ensure data access is strictly controlled by user roles (Teacher, Student, Parent).
- **User Relationships**: Carefully define and enforce relationships (e.g., Parents linked to Students, Students linked to Teachers/Classes) using foreign keys and RLS policies.
- **Parent Data Access**: RLS policies must ensure parents can *only* see data related to their own children.

## 📈 Supabase pgvector for RAG
- **Curriculum Documentation**: Use `supabase pgvector` for storing and performing Retrieval-Augmented Generation (RAG) on curriculum documentation.
- **Embedding Management**: Ensure proper management of `curriculum_embeddings` table, including content and metadata for effective RAG.

## ⚡ Real-time Updates
- **Supabase Real-time Subscriptions**: Utilize Supabase's real-time capabilities for live updates on grades, messages, assignments, and notifications.
- **Optimistic Updates**: Implement optimistic updates for improved user experience on form submissions and data modifications, reducing perceived latency.

## 🔄 Database Migrations & Seeding
- **Migrations**: Manage database schema changes using Supabase migrations in `supabase/migrations/`.
- **Seed Data**: Use `supabase/seed.sql` for initial data population necessary for development and testing. 