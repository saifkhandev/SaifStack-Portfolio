# Saif Stack 🚀

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white&labelColor=20232a)
![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white&labelColor=20232a)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-4-06B6D4?logo=tailwindcss&logoColor=white&labelColor=20232a)
![Three.js](https://img.shields.io/badge/Three.js-3D-000000?logo=three.js&logoColor=white&labelColor=20232a)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black&labelColor=20232a)
![GSAP](https://img.shields.io/badge/GSAP-Animations-88CE02?logo=greensock&logoColor=white&labelColor=20232a)
![Responsive](https://img.shields.io/badge/Responsive-Yes-brightgreen?labelColor=20232a)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?labelColor=20232a)

A modern, interactive 3D developer portfolio built with React, Three.js, and GSAP — designed to showcase my work, skills, and experience through an engaging, animation-rich experience rather than a static page.

**Live Site:** [Add your Netlify link here once deployed]
**Repository:** [Add your GitHub repo link here]

---

## 📖 About

Saif Stack is my personal developer portfolio, built to present who I am as a developer in a way that's visually memorable rather than a plain resume-style website. It combines 3D models rendered directly in the browser, scroll-based animations, and a clean, responsive layout to walk visitors through my work, tech stack, professional experience, and a way to get in touch — all in a single smooth-scrolling page.

This project was built by following a guided tutorial and then extended and customized with my own content, sections, styling decisions, and integrations (like a fully working contact form).

---

## ✨ Features

- **Interactive 3D Hero Section** — A real-time, orbit-controlled 3D room scene rendered with Three.js / React Three Fiber
- **Animated Tech Stack Section** — 3D rotating models representing different technologies I work with, alongside labeled skill categories
- **Scroll-Triggered Animations** — Smooth entrance and reveal animations throughout the site powered by GSAP and ScrollTrigger
- **Experience Timeline** — A detailed breakdown of my professional experience, including internships and development roles, each with role-specific responsibilities
- **Client/Peer Testimonials** — A dedicated section highlighting feedback and reviews
- **Animated Statistics Counter** — Live count-up animations for key stats (years of experience, projects completed, etc.)
- **Functional Contact Form** — A real, working contact form integrated with EmailJS, so messages sent through the site are delivered directly to my inbox — no backend server required
- **3D Contact Experience** — A dedicated Three.js canvas alongside the contact form for a more immersive feel
- **Fully Responsive Design** — Built mobile-first with Tailwind CSS, adapting cleanly across phone, tablet, and desktop screens
- **Social Links Integration** — Direct links to my GitHub, LinkedIn, and Instagram profiles

---

## 🛠️ Built With

**Core**
- [React 19](https://react.dev/) — UI library
- [Vite](https://vite.dev/) — Build tool and dev server

**Styling**
- [Tailwind CSS v4](https://tailwindcss.com/) — Utility-first CSS framework

**3D & Animation**
- [Three.js](https://threejs.org/) — 3D rendering engine
- [@react-three/fiber](https://docs.pmnd.rs/react-three-fiber) — React renderer for Three.js
- [@react-three/drei](https://github.com/pmndrs/drei) — Useful helpers for React Three Fiber
- [@react-three/postprocessing](https://github.com/pmndrs/react-postprocessing) — Visual post-processing effects
- [GSAP](https://gsap.com/) + [@gsap/react](https://gsap.com/resources/React) — Scroll-based and entrance animations

**Utilities**
- [EmailJS](https://www.emailjs.com/) (`@emailjs/browser`) — Client-side contact form email delivery
- [React CountUp](https://www.npmjs.com/package/react-countup) — Animated number counters
- [React Responsive](https://www.npmjs.com/package/react-responsive) — Responsive breakpoint handling

**Tooling**
- [ESLint](https://eslint.org/) — Code linting

---

## 📂 Project Structure

```
SaifStack/
├── public/
│   ├── images/          # Static images, icons, and logos
│   └── models/          # 3D models (.glb files) for Three.js scenes
├── src/
│   ├── components/      # Reusable UI components
│   │   ├── HeroModels/   # 3D scene components for the Hero section
│   │   ├── Models/       # Individual 3D model components
│   │   ├── AnimatedCounter.jsx
│   │   ├── Button.jsx
│   │   ├── ContactExperience.jsx
│   │   ├── GlowCard.jsx
│   │   ├── NavBar.jsx
│   │   └── TitleHeader.jsx
│   ├── constants/        # Centralized site content (nav links, testimonials, experience data, etc.)
│   ├── sections/          # Page sections assembled in App.jsx
│   │   ├── Hero.jsx
│   │   ├── ShowcaseSection.jsx
│   │   ├── LogoSection.jsx
│   │   ├── FeatureCards.jsx
│   │   ├── ExperienceSection.jsx
│   │   ├── TechStack.jsx
│   │   ├── Testimonials.jsx
│   │   ├── Contact.jsx
│   │   └── Footer.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .env                  # EmailJS credentials (not committed to version control)
├── package.json
└── vite.config.js
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm (comes bundled with Node.js)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Set up environment variables

   Create a `.env` file in the root directory and add your own [EmailJS](https://www.emailjs.com/) credentials so the contact form can send emails:
   ```
   VITE_APP_EMAILJS_SERVICE_ID=your_service_id
   VITE_APP_EMAILJS_TEMPLATE_ID=your_template_id
   VITE_APP_EMAILJS_PUBLIC_KEY=your_public_key
   ```

4. Run the development server
   ```bash
   npm run dev
   ```

   The site will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

This generates an optimized production build in the `dist/` folder, ready to deploy.

---

## 📬 Contact

Feel free to reach out through the contact form on the live site, or connect with me directly:

- **GitHub:** [github.com/saifkhandev](https://github.com/saifkhandev)
- **LinkedIn:** [linkedin.com/in/saifstacks](https://www.linkedin.com/in/saifstacks)
- **Instagram:** [instagram.com/notthatpretty.saiff](https://www.instagram.com/notthatpretty.saiff/)

---

## 📝 License

This project is open for reference and learning purposes. If you use parts of this project's structure or code, credit is appreciated.

---

Built with 💻 and a lot of ☕ by **Muhammad Saifullah Khan**
