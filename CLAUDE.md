# CLAUDE.md - HomeStore Marketplace

## Project Overview

This web store is a marketplace for selling homewear, accessories, and gadgets at giveaway prices.

## Tech Stack

- Next.js 14
- TypeScript 4.2
- Tailwind CSS 4

## Project Structure

homestore-marketplace/
├── frontend/
│ └── src/
│ ├── app/
│ │ ├── (auth)/
│ │ ├── (dashboard)/
│ │ ├── api/
│ │ ├── layout.tsx
│ │ └── globals.css
│ ├── components/
│ │ ├── ui/
│ │ ├── layout/
│ │ └── features/
│ ├── hooks/
│ ├── utils/
│ ├── types/
│ └── services/
├── backend/
│ └── src/
│ ├── routes/
│ ├── controllers/
│ ├── models/
│ ├── middleware/
│ ├── services/
│ ├── utils/
│ ├── types/
│ └── config/
├── package.json
├── tsconfig.json
├── tailwind.config.js
├── .env.example
└── README.md

text

## NPM Commands

- `npm run dev` - Start development server
- `npm run test` - Run tests
- `npm start` - Start production server

## Architecture Rules

- Frontend and backend are in separate directories
- Single unified package.json file at root
- Use type module convention (ES Modules)
- Use functional components only (no class components)
- TypeScript for all files

## Code Conventions

- Functional components with TypeScript interfaces
- ES Module imports/exports (import/export, not require/module.exports)
- Tailwind CSS for styling
- Component-based architecture with separation of concerns

## Getting Started

1. Clone repository
2. Run `npm install`
3. Run `npm run dev` for development
4. Run `npm run test` for testing
5. Run `npm start` for production

## Important Notes

- All components must be functional, not class-based
- Use TypeScript types for props and state
- Keep frontend and backend code in their respective directories
- Follow Next.js 14 App Router conventions
