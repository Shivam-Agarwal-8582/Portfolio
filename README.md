# Shivam Agarwal — Developer Portfolio

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Portfolio-7C3AED?style=for-the-badge&logo=vercel)](https://shivam-portfolio-2026-tau.vercel.app/)
[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-6-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

A modern, responsive developer portfolio for **Shivam Agarwal**, a Computer Science Engineering student and aspiring Software Development Engineer. The site highlights my profile, technical skills, education, coding activity, featured projects, and downloadable resume.

**Live website:** [shivam-portfolio-2026-tau.vercel.app](https://shivam-portfolio-2026-tau.vercel.app/)

## ✨ Highlights

- Responsive layouts optimized for desktop, tablet, and mobile devices
- Light and dark themes with persistent user preference
- Animated sections and interface elements powered by Framer Motion
- Dedicated sections for about, skills, projects, education, and coding profiles
- Direct resume download, GitHub, LinkedIn, LeetCode, email, and live-project links
- Modular React components and typed portfolio data
- Vite-powered development with a fast production build

## 🛠️ Tech Stack

| Area            | Technologies         |
| --------------- | -------------------- |
| Frontend        | React 19, TypeScript |
| Styling         | Tailwind CSS, CSS3   |
| Animation       | Framer Motion        |
| Icons           | Lucide React         |
| Build Tool      | Vite                 |
| Deployment      | Vercel               |
| Package Manager | npm                  |
| Quality Tool    | Oxlint               |

## 📂 Project Structure

```text
Portfolio/
├── public/                 # Static files, including the resume
├── src/
│   ├── assets/             # Local image assets
│   ├── components/         # Portfolio UI sections and components
│   ├── context/            # Theme context and application state
│   ├── data/               # Portfolio content and project definitions
│   ├── types/              # Shared TypeScript types
│   ├── App.tsx             # Root application component
│   ├── App.css             # Component-level styles
│   ├── index.css           # Global styles and Tailwind directives
│   └── main.tsx            # React application entry point
├── index.html
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── vite.config.ts
```

## 🚀 Featured Work

| Project                                                                                          | Description                                                                                        | Technologies                                    |
| ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| [AI-Powered ATS Resume Analyzer](https://github.com/Shivam-Agarwal-8582/AI-Resume-Analyzer)      | Resume scoring service with document parsing, keyword-gap analysis, and Gemini-based optimization. | Spring Boot, Gemini API, MySQL, PDFBox, React   |
| [Smart Seat & Ticket Reservation](https://github.com/Shivam-Agarwal-8582/seat-management-system) | Concurrency-safe hybrid workspace and ticket reservation platform with role-based access.          | Spring Boot, React, MySQL, JWT                  |
| [LRU Cache Visualizer](https://github.com/Shivam-Agarwal-8582/LRU-cache-Updated)                 | Interactive O(1) cache simulator with custom HashMap and doubly linked list implementations.       | React, JavaScript, Data Structures              |
| [StoreCraft E-Commerce](https://github.com/Shivam-Agarwal-8582/E-commerce-Webiste)               | MERN retail platform with inventory, cart, filtering, and admin order management.                  | React, Redux Toolkit, Node.js, Express, MongoDB |

## ⚙️ Local Development

### Prerequisites

- Node.js 18 or newer
- npm

### Installation

```bash
# Clone the repository
git clone https://github.com/Shivam-Agarwal-8582/Portfolio.git

# Enter the project directory
cd Portfolio

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open the local URL displayed by Vite, usually [http://localhost:5173](http://localhost:5173).

### Available Scripts

| Command           | Purpose                                      |
| ----------------- | -------------------------------------------- |
| `npm run dev`     | Start the local Vite development server      |
| `npm run build`   | Type-check and generate the production build |
| `npm run lint`    | Run Oxlint across the project                |
| `npm run preview` | Preview the production build locally         |

## 🌍 Deployment

The project can be deployed to any static hosting service that supports a Vite build.

```bash
npm run build
```

The generated production files are written to the `dist/` directory. The current version is hosted on [Vercel](https://vercel.com/) using the repository's root configuration.

## ✏️ Customizing Portfolio Content

Most portfolio information is centralized in:

- `src/data/portfolioData.ts` — personal details, projects, skills, education, and coding profiles
- `src/components/` — reusable visual sections
- `src/index.css` and `tailwind.config.js` — colors, themes, and global styling

## 🤝 Connect

- **Portfolio:** [Visit website](https://shivam-portfolio-2026-tau.vercel.app/)
- **GitHub:** [Shivam-Agarwal-8582](https://github.com/Shivam-Agarwal-8582)
- **LinkedIn:** [Shivam Agarwal](https://www.linkedin.com/in/shivam-agarwal-896956312/)
- **LeetCode:** [Shivam_Agarwal_8582](https://leetcode.com/u/Shivam_Agarwal_8582/)
- **Email:** [shivamagarwalblp@gmail.com](mailto:shivamagarwalblp@gmail.com)

---

<p align="center">Built with React, TypeScript, Tailwind CSS, and Framer Motion.</p>
