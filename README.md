# Client (Next.js)

This is the **client-side** of the project, built with [Next.js](https://nextjs.org/), React 19, and Tailwind CSS 4.

## Features
- Modern React (v19) with Next.js 15.3+
- Routing, data fetching, and SSR/SSG support
- Tailwind CSS 4 for styling
- Axios for API requests
- Proxy setup for local API calls

## Getting Started

### Prerequisites
- Node.js (v18 or later recommended)
- npm

### Setup
```bash
cd client
npm install
```

### Running in Development
```bash
npm run dev
```
- The app will start on [http://localhost:3000](http://localhost:3000) (or next available port).
- Requests to `/api` are proxied to the server on port 5000.

### Building for Production
```bash
npm run build
npm start
```

## Scripts
- `dev`: Start Next.js in development mode
- `build`: Build for production
- `start`: Start the production server
- `lint`: Run ESLint

## Folder Structure
- `src/` - Main source code
- `public/` - Static files

## Environment Variables
- See `.env.local` for client-side environment variables (if needed)

## Dependencies
- next, react, react-dom, react-router-dom, axios, tailwindcss, postcss, autoprefixer, lightningcss

## Dev Dependencies
- TypeScript, ESLint, @types/*, etc.

## Notes
- Make sure the server is running on port 5000 for API requests.
- For any issues with native modules (e.g., lightningcss), try deleting `node_modules` and reinstalling.
