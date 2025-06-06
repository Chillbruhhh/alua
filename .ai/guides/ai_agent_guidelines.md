# AI Agent Integration Guidelines

## 🤖 Agent-Based Architecture
- **Specialized Agents**: Develop specialized LangChain.js agents for distinct educational tasks (e.g., `CurriculumScraperAgent`, `LessonPlanGeneratorAgent`, `AssessmentCreatorAgent`).
- **OpenRouter Integration**: Configure OpenRouter for cost-effective access to multiple LLM models, ensuring flexibility and efficiency.

## 📚 Retrieval-Augmented Generation (RAG)
- **Curriculum Compliance**: Implement RAG using Supabase pgvector to ensure all generated educational content (e.g., lesson plans) is compliant with curriculum standards.
- **Vector Store Management**: Maintain and update the `curriculum_embeddings` table to support accurate and relevant RAG.

## 🔗 Multi-Agent Workflows
- **Agent Collaboration**: Design workflows where agents can collaborate to achieve complex tasks, such as chaining a `CurriculumValidatorAgent` with a `LessonGeneratorAgent`.
- **Agent Memory**: Utilize Supabase for agent memory to maintain conversation history and context across interactions, improving agent performance.

## 🎯 Specific Agent Responsibilities
- **CurriculumScraperAgent**: Responsible for automated scraping of state education standards from specified websites.
- **LessonPlanGeneratorAgent**: Creates grade-appropriate, curriculum-aligned lesson plans, leveraging RAG capabilities.
- **LessonValidatorAgent**: Validates generated lessons against state and federal education requirements.
- **AssessmentCreatorAgent**: Generates quizzes, tests, and rubrics based on lesson content and standards.
- **GradingAssistantAgent**: Provides automated grading for objective assessments.
- **DifferentiationAgent**: Adapts educational content for various learning styles and abilities. 