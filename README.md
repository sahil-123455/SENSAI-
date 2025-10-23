🎓 SENSAI: Your AI Career Coach for Professional Success
🌟 Overview
SENSAI is a sophisticated, full-stack AI platform designed to accelerate professional careers. It leverages advanced Gemini AI to deliver personalized guidance, generate job-ready content, and provide data-driven insights into the current job market.

The platform is built to simulate real-world career scenarios, ensuring users are fully prepared for interviews, resume screenings (ATS), and career progression.

✨ Key Features
AI Mock Interview Prep: Generates role-specific technical and behavioral questions, tracks performance trends using charts, and provides AI-generated improvement tips after each quiz.

AI Resume Builder: Features an "Improve with AI" tool to rewrite experience descriptions for ATS optimization, allows real-time markdown editing, and supports PDF download of the final resume.

AI Cover Letter Generator: Analyzes job descriptions and user profiles to craft tailored cover letters.

Industry Insights Dashboard: Displays weekly updated metrics on in-demand skills, salary trends (Min/Median/Max), market outlook, and growth rate.

Data Reliability: Utilizes background Cron Jobs (Injest) to ensure all Industry Insight data is consistently up-to-date.

🚀 Tech Stack

Frontend Framework: Next.js (utilizing the latest App Router)

Backend/AI: Gemini API (for core AI functionalities, content generation, and analysis)

Styling/UI: Tailwind CSS and Shadcn UI (for component library)

Database: PostgreSQL (hosted on Neon DB)

ORM (Object-Relational Mapping): Prisma (for type-safe database access)

Authentication: Clerk (for user management and sign-in/sign-up)

Background Jobs/Cron: Injest (for scheduling weekly data updates)

Form Management: React Hook Form and Zod (for validation)

Charting/Graphs: Recharts (for displaying performance and salary trends)

Language: TypeScript (used across the entire codebase)

Deployment: Vercel
