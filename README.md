# Test Project

A Node.js web application built with TypeScript and Next.js.

## Tech Stack

| Category | Technology |
|----------|------------|
| Project Type | Web Application |
| Runtime | Node.js |
| Language | TypeScript |
| Web Framework | Next.js (App Router) |
| Package Manager | npm |
| Styling | TBD (e.g. Tailwind CSS) |
| Linting / Formatting | ESLint, Prettier |

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- npm (included with Node.js)

## Getting Started

1. Clone the repository:

```bash
git clone <repository-url>
cd test-project
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the project root (if needed):

```bash
cp .env.example .env
```

4. Start the development server:

```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm install` | Install project dependencies |
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm run start` | Run the production server |
| `npm run lint` | Run ESLint |

> **Note:** Next.js scripts will be available after the project is initialized with Next.js.

## Project Structure

```
test-project/
├── app/              # Next.js App Router pages and layouts
├── public/           # Static assets
├── cursor.md         # Cursor AI project context
├── package.json
└── README.md
```

## Development Guidelines

- Follow existing project conventions when writing code
- Keep changes small and focused
- Read relevant files before adding new features or making large changes

## License

ISC
