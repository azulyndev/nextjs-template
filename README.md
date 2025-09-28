# Next.js Template

To create a new project using this template:

```bash
npx degit azulyndev/nextjs-template my-new-project
cd my-new-project
npm install


## Project Structure
nextjs-template/
├── public/              # Static assets
│   ├── file.svg
│   ├── globe.svg
│   ├── next.svg
│   ├── vercel.svg
│   └── window.svg
├── src/                 # Main source directory
│   ├── app/             # App Router pages and layouts
│   │   ├── layout.js    # Root layout (wraps all pages)
│   │   ├── page.js      # Homepage
│   │   └── [slug]/      # Dynamic route example
│   │       └── page.js
│   ├── components/      # Reusable UI components
│   │   ├── layout/      # Structural components (e.g., Header, Footer)
│   │   ├── ui/          # Presentational components (e.g., Button, Card)
│   │   └── index.js     # Export all components
│   ├── lib/             # Utilities and helpers
│   │   ├── utils.js     # General utilities
│   │   └── constants.js # App-wide constants
│   ├── hooks/           # Custom React hooks
│   ├── assets/          # Images, fonts, etc. (beyond public/)
│   │   ├── images/
│   │   └── fonts/
│   ├── styles/          # Optional: modular or global styles
│   │   └── globals.css  # Tailwind directives
│   └── types/           # For future TypeScript conversion
├── data/                # Static data (e.g., JSON for initial content)
├── tests/               # Unit and integration tests
│   ├── components/
│   └── app/
├── .eslintrc.json       # ESLint config
├── .gitignore           # Git ignore file
├── jsconfig.json        # JS config (for path resolution)
├── next.config.mjs      # Next.js config
├── package-lock.json    # Lock file
├── package.json         # Project dependencies and scripts
└── postcss.config.mjs   # PostCSS config (for Tailwind)
