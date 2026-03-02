# MEMORY-CRYSTAL

Company website built with TypeScript/JavaScript.

## Project Overview

This is the company website for MEMORY-CRYSTAL. It serves as the primary web presence for the company.

## Tech Stack

- **Language**: TypeScript / JavaScript
- **Package manager**: (update when decided — npm / yarn / pnpm)
- **Framework**: (update when decided — e.g. Next.js, Astro, Vite + React)
- **Styling**: (update when decided — e.g. Tailwind CSS, CSS Modules)
- **Deployment**: (update when decided — e.g. Vercel, Netlify, AWS)

## Getting Started

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
/
├── public/          # Static assets (images, fonts, favicons)
├── src/
│   ├── components/  # Reusable UI components
│   ├── pages/       # Page components / routes
│   ├── styles/      # Global styles
│   └── types/       # TypeScript type definitions
└── CLAUDE.md
```

> Update this structure once the project scaffolding is in place.

## Development Guidelines

- Keep components small and focused on a single responsibility
- Co-locate styles with their components where possible
- Use TypeScript strictly — avoid `any`
- Prefer semantic HTML elements for accessibility
- Optimize images before committing (use WebP/AVIF where supported)

## Commands

| Command           | Purpose                       |
|-------------------|-------------------------------|
| `npm run dev`     | Start local dev server        |
| `npm run build`   | Production build              |
| `npm run lint`    | Run linter                    |
| `npm run typecheck` | Run TypeScript type check   |
| `npm test`        | Run tests                     |

> Update these once the actual scripts are defined in `package.json`.

## Notes for Claude

- This is a company website — prioritize clean, accessible, and performant output
- Avoid over-engineering; prefer simple, maintainable solutions
- Do not commit placeholder content or lorem ipsum text
- Design decisions should be consistent with the brand identity
