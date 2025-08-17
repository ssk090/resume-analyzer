# Resume Analyzer (Resumate)

Resumate is a modern web application for analyzing and improving your resume using AI. Upload your resume, get instant feedback, and track your application ratings. Built with React Router, TypeScript, TailwindCSS, and Puter.js for authentication, file management, and AI feedback.

## Features

- 📝 Upload and analyze resumes
- 🤖 AI-powered feedback and scoring (ATS, content, style, skills, structure)
- 📊 Track application ratings and feedback history
- 🔒 Authentication via Puter.js
- 🚀 Server-side rendering (SSR) with React Router
- 🎨 Modern UI with TailwindCSS
- ⚡ Hot Module Replacement (HMR)
- 📦 Asset bundling and optimization

## Getting Started

### Installation

Install dependencies:

```bash
npm install
# or
pnpm install
```

### Development

Start the development server:

```bash
npm run dev
# or
pnpm run dev
```

Visit [http://localhost:5173](http://localhost:5173) in your browser.

## Building for Production

Create a production build:

```bash
npm run build
# or
pnpm run build
```

## Deployment

### Docker

Build and run with Docker:

```bash
docker build -t resume-analyzer .
docker run -p 3000:3000 resume-analyzer
```

### Manual Deployment

Deploy the output of `npm run build` (or `pnpm run build`) to your preferred Node hosting platform.

## Environment & Configuration

- Uses [Puter.js](https://puter.com/) for authentication, file storage, and AI feedback
- Configure SSR/SPA mode in `react-router.config.ts`
- Vite and TailwindCSS for fast development and styling

## File Structure

```
├── app/
│   ├── components/        # UI components (Navbar, ResumeCard, ScoreCircle)
│   ├── lib/               # Puter.js integration
│   ├── routes/            # Route files (auth, home, constants)
│   ├── app.css            # Global styles
│   └── root.tsx           # App entry
├── public/                # Static assets (images, icons)
├── types/                 # TypeScript types
├── package.json           # Project metadata and scripts
├── Dockerfile             # Docker setup
├── vite.config.ts         # Vite configuration
├── tsconfig.json          # TypeScript configuration
```

## Contributing

Pull requests and issues are welcome!

## License

MIT

---
Built with ❤️ using React Router, Vite, and Puter.js.
