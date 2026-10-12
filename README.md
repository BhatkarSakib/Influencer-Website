# Influencer Website

> A modern, responsive frontend reimagining the personal website of Elizabeth Filips.

![React](https://img.shields.io/badge/React-19.1.0-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7.0.4-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.1.11-38B2AC?logo=tailwindcss&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

---

## 📋 Project Overview

This repository contains the **frontend** of a reimagined influencer website, inspired by [Elizabeth Filips](https://www.elizabethfilips.com/). Originally developed during a 10-day hackathon as part of the **Sheryian Coding School** cohort, the goal was to elevate user experience and visual appeal by creating a custom React + Tailwind CSS frontend while preserving the essence and content of the original site.

The project is actively evolving, with two major pages completed and more planned for future development.

---

## ✨ Features

### ✅ Completed Features

| Page | Features |
|------|----------|
| **Landing Page** | • Modernized hero section with animated text, stylized buttons, and polished CTA<br>• Responsive navigation header and footer with dynamic newsletter signup and social links<br>• Sections for popular book notes, YouTube videos, and podcasts<br>• Seamless responsiveness across all devices |
| **Book Notes Page** | • Structured JSON-based content scraped and transformed from the original site<br>• Fully desktop and mobile responsive layout<br>• Smooth Swiper.js carousel integration<br>• Category-based filtering powered by dynamic routes (e.g., `/booknotes/medicines`)<br>• Performance enhancements including lazy loading for book cards |

### 🔜 Upcoming Features

- Newsletter Page for lead generation and subscriber engagement
- Dynamic form validation and user feedback mechanisms
- Mobile-first optimization for all new pages
- Enhanced UX with subtle animations and accessibility standards
- Integration of a lightweight backend or CMS to replace local JSON files

---

## 🛠 Tech Stack

| Category | Technologies |
|----------|-------------|
| **Frontend** | React 19, Tailwind CSS 4, React Router DOM 7 |
| **Components & State** | Context API, reusable components (Navbar, Carousel, NewsletterInput) |
| **Assets** | Local JSON files for content — simulating a CMS |
| **Animations & Effects** | Swiper.js, CSS animations, react-type-animation |
| **Additional Libraries** | react-icons, react-player, clsx, DOMPurify |
| **Build Tool** | Vite 7 |
| **Linting** | ESLint 9 with React Hooks and React Refresh plugins |
| **Deployment** | Netlify (live site) |

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** v14 or higher
- **npm** (comes with Node.js) or **yarn**

### Installation

# Clone the repository
git clone https://github.com/BhatkarSakib/Influencer-Website.git

# Navigate to the frontend directory
cd Influencer-Website/frontend

# Install dependencies
npm install

Development
bash
# Start the development server
npm run dev

# The app will be available at http://localhost:5173
Production Build
bash
# Create a production build
npm run build

# Preview the production build locally
npm run preview
Linting
bash
# Run ESLint
npm run lint
📁 Project Structure
text
frontend/
├── public/                     # Static assets
├── src/
│   ├── components/
│   │   ├── layout/             # Navbar, Footer
│   │   └── shared/             # Shared UI elements (NewsletterInput, Carousel)
│   ├── context/                # Global context + JSON fetch logic
│   ├── pages/
│   │   ├── LandingPage/
│   │   └── BookNotesPage/
│   ├── router/                 # React Router setup
│   ├── assets/                 # Images, icons, fonts
│   ├── App.jsx                 # Root component
│   ├── index.css               # Global styles
│   └── main.jsx                # Entry point
├── index.html                  # HTML template
├── package.json                # Project metadata and scripts
├── tailwind.config.js          # Tailwind CSS configuration
├── postcss.config.js           # PostCSS configuration
├── vite.config.js              # Vite configuration
├── eslint.config.js            # ESLint configuration
└── README.md                   # This file
📜 Available Scripts
Script	Description
npm run dev	Starts the Vite development server with HMR
npm run build	Creates an optimized production build in dist/
npm run preview	Previews the production build locally
npm run lint	Runs ESLint across the project
🌐 Live Demo
Live Preview: https://hackthon-reimagine-influencer-website.netlify.app/

🔄 Next Steps (To Be Implemented)
□ Design and build the Newsletter Page for lead generation and subscriber engagement
□ Add dynamic form validation and user feedback mechanisms
□ Continue mobile-first optimization for all new pages
□ Enhance UX with subtle animations and accessible standards
□ Integrate a lightweight backend or CMS to replace local JSON files
🙏 Acknowledgments
Sheryian Coding School and our peer cohort for guidance and inspiration throughout the hackathon.

Elizabeth Filips for the original website design and content that inspired this reimagination.

The open-source community for the tools and libraries that made this project possible.

🤝 Contributing
This project is actively evolving. Contributions, feedback, and issues are welcome!

Fork the repository

Create a feature branch (git checkout -b feature/amazing-feature)

Commit your changes (git commit -m 'Add some amazing feature')

Push to the branch (git push origin feature/amazing-feature)

Open a Pull Request

Please ensure your code follows the existing style conventions and passes the linting checks before submitting a PR.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

📬 Contact
For questions, feedback, or collaboration opportunities, please open an issue on GitHub or reach out to the repository maintainer.
