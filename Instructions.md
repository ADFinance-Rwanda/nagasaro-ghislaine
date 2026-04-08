# Junior Intern Assignment: Full-Stack Blog Application

## Project Overview
Build a complete **DevBlog** – a personal blog web application where users can create, publish, and interact with blog posts.

The goal is to demonstrate your ability to build a **full-stack** web application from scratch, including a responsive frontend, a clean REST API backend, and a relational database. The project should be functional, well-structured, and easy to run locally.

**Important**: This assignment is designed to evaluate **your own coding and problem-solving skills**. You may use AI tools for small helper questions (e.g., syntax), but the architecture, logic, and implementation must be your own work. You will be asked to explain every part of the code during the technical interview.

## Required Tech Stack
- **Frontend**: Angular **or** Next.js (you choose one)
- **Backend**: Node.js + Express.js
- **Database**: PostgreSQL (use raw queries or any lightweight ORM if you prefer – Prisma is **not** required)
- **Language**: TypeScript (strongly recommended)
- **Authentication**: JWT
- **Other allowed libraries**: bcryptjs, cors, dotenv, express-validator (or similar for validation)

**You may NOT use** full-stack frameworks like NestJS or Supabase/ Firebase that hide the backend logic.

## Functional Requirements (Must be fully implemented)

### 1. User Authentication
- Register (name, email, password)
- Login
- Logout
- Protected routes for creating/editing posts (only authenticated users)

### 2. Blog Posts (CRUD)
- Create a post: title, content (plain text or markdown), category (dropdown: Tech, Lifestyle, Travel, etc.)
- View all published posts (public page)
- View single post with details
- Edit / Delete **only your own** posts

### 3. Comments
- Authenticated users can add comments on any post
- View all comments under a post (sorted by newest first)

### 4. Additional Features
- Search posts by title or content (basic full-text search)
- Filter posts by category
- Responsive design (mobile-friendly)
- Simple pagination (10 posts per page on the list view)

### 5. Backend API Requirements
- RESTful routes with proper HTTP status codes and JSON responses
- Clear separation of concerns (controllers, services, routes)
- Basic error handling and validation on all endpoints

## Technical Requirements
- Use environment variables (`.env.example` must be provided)
- Secure password hashing with bcrypt
- Proper CORS configuration
- At least 3 database tables: `users`, `posts`, `comments` with correct foreign keys and indexes
- Input validation on all user inputs
- Clean folder structure (frontend and backend should be in one repo or clearly separated with clear instructions)

## Submission Instructions
1. Create a **public GitHub repository** named `devblog-junior-assignment`.
2. Your repo **must** contain:
   - Complete source code
   - `README.md` (see template below)
   - `.env.example`
   - SQL script or migration file to create the database schema
   - Screenshots of the running application (at least 4: login, post list, single post + comments, create post)
3. **Do not** commit any `.env` file or sensitive data.
4. Share the GitHub repository link with us.

### README.md Template (must include)
- Project description
- Tech stack used
- How to set up and run locally (step-by-step: database, backend, frontend)
- Environment variables explanation
- Any design decisions you made
- Challenges you faced and how you solved them

## Evaluation Criteria
- Completeness of features (50%)
- Code quality, organization, and readability (20%)
- Database design and API design (15%)
- UI/UX and responsiveness (10%)
- README quality and setup instructions (5%)

**Estimated time**: 8–12 hours (spread over 3–5 days).

We will clone your repo, run it locally, and review the code. Be ready for a live coding/discussion round.

---

**Good luck!** We are excited to see what you build. If you have any questions about the requirements, ask before starting.