Project Description
CineSeek is a modern movie discovery application built with Next.js, TypeScript, and Tailwind CSS. The application allows users to browse movies from the MoviesDatabase API, view movie details, and search for films by year or genre. The project focuses on creating a responsive, well-structured web application with proper API integration and TypeScript typing.

Learning Objectives
Understanding API documentation and integration
Implementing TypeScript interfaces for API responses
Creating reusable React components
Building a responsive layout with Tailwind CSS
Managing application state for filtering and pagination
Implementing proper error handling and loading states
Setting up Next.js API routes for server-side data fetching
Environment variable management for API keys
Requirements
Technical Stack
Next.js 14 (Pages Router)
TypeScript
Tailwind CSS
Font Awesome icons
MoviesDatabase API
Development Requirements
Node.js (v16 or higher)
npm or yarn
Git for version control
File Structure
alx-movie-app/
├── components/
│   ├── commons/
│   │   ├── Button.tsx
│   │   ├── Loading.tsx
│   │   └── MovieCard.tsx
│   └── layouts/
│       ├── Footer.tsx
│       ├── Header.tsx
│       └── Layout.tsx
├── interfaces/
│   └── index.ts
├── pages/
│   ├── api/
│   │   └── fetch-movies.ts
│   ├── movies/
│   │   └── index.tsx
│   ├── _app.tsx
│   └── index.tsx
├── public/
├── styles/
│   └── globals.css
├── .env.local
├── .eslintrc.json
├── .gitignore
├── next.config.js
├── package.json
└── tsconfig.json
Best Practices
Code Quality
TypeScript interfaces for all props and API responses
Component-based architecture with clear separation of concerns
Proper error handling in API requests
Loading states for better UX
Environment variables for sensitive data
Performance
Client-side navigation with Next.js router
Efficient API calls with proper pagination
Responsive design with Tailwind CSS
Image optimization with Next.js Image component
Maintainability
Consistent code formatting
Clear folder structure
Reusable components
Comprehensive prop typing
Proper documentation in README
API Integration
The application uses the MoviesDatabase API with the following key endpoints: - /titles - Main endpoint for fetching movie data - Supports filtering by year and genre - Implements pagination for browsing through results

Authentication
API key authentication via headers
Environment variable storage for API key
Server-side API route to protect client-side exposure of keys
Error Handling
Loading component for pending states
Try/catch blocks in API routes
Status code checking for API responses
Type guards for API data
Usage Limits
API rate limiting considerations
Pagination to limit request size
Client-side caching of responses where appropriate
Error boundaries for graceful failure
