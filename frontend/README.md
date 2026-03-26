# 🚀 Influencer Websites

**Live Preview:** [View on Netlify](https://hackthon-reimagine-influencer-website.netlify.app/)  
**Original Inspiration:** [Elizabeth Filips](https://www.elizabethfilips.com/)

---

## 🧠 Project Overview

This is a reimagined version of Elizabeth Filips’ personal website, developed during a 10-day hackathon as part of the Sheryian Coding School cohort. The goal was to elevate user experience and visual appeal by creating a custom React + Tailwind frontend, while preserving the essence and content of the original site.

---

## ✅ Completed Features (Pages 1 & 2)

### 1. Landing Page

- Modernized **hero section** with animated text, stylized buttons, and a polished CTA.
- Responsive **navigation header** and **footer** with dynamic newsletter signup and social links.
- Sections for **popular book notes**, YouTube videos, and podcasts—designed with seamless responsiveness in mind.

### 2. Book Notes Page

- Structured **JSON-based content** scraped and transformed from the original site.
- Fully **desktop and mobile responsive** layout with smooth Swiper.js carousel integration.
- **Category-based filtering** powered by dynamic routes (e.g., `/booknotes/medicines`).
- Performance enhancements such as **lazy loading** for book cards.

---

## 🧰 Tech Stack

- **Frontend:** React, Tailwind CSS, React Router
- **Components & State:** Context API, reusable components (e.g., Navbar, Carousel)
- **Assets:** Local JSON files for content — simulating a CMS
- **Animations & Effects:** Swiper.js for interactive sliders, CSS animations
- **Deployment:** Netlify (live site)

---

## 🛠️ Getting Started

**Prerequisites:** Node.js v14+ and npm

```bash
git clone https://github.com/PrajwalGhadi/Hackthon_Re-Imagine_Influencer_Websites.git

cd Hackthon_Re-Imagine_Influencer_Websites

npm install
npm run dev      # For local development (Vite)
npm run build    # To create a production build
npm run preview  # Preview the build locally
```

---

## 📋 Project Structure

```
src/
├── components/
│   ├── layout/            # Navbar, Footer
│   ├── shared/            # Shared UI elements (NewsletterInput, Carousel)
├── pages/
│   ├── LandingPage/
│   └── BookNotesPage/
├── context/               # Global context + JSON fetch logic
├── router/                # React Router setup
├── assets/                # Images, icons, fonts
```

---

## 📌 Next Steps (To Be Implemented)

- Design and build the **Newsletter Page** for lead generation and subscriber engagement.
- Add **dynamic form validation** and user feedback mechanisms.
- Continue **mobile-first optimization** for all new pages.
- Enhance UX with subtle **animations** and accessible standards.
- Integrate a lightweight **backend or CMS** to replace local JSON files.

---

## 🙌 Acknowledgments

- Thank you to **Sheryian Coding School** and our peer cohort for guidance and inspiration.
- Inspired by the clean design and thoughtful structure of Elizabeth Filips’ original site.

---

### 🎯 Feedback & Contributions

This project is actively evolving—if you'd like to contribute, provide feedback, or report issues, feel free to open an issue or PR on GitHub. Your ideas and enhancements are welcome!

---

## ✅ TL;DR

A modern, responsive, and reusable React frontend that brings fresh life to Elizabeth Filips’ influencer website—built with scalability and polish, just two pages done, but many more to come!
