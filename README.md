**Next-Generation-AI-Portfolio-README**

# Next Generation AI Portfolio

A next generation, modern, interactive developer portfolio built with React, TypeScript, TailwindCSS, Three.js, Framer Motion and AI-powered features. This project showcases your skills, projects, and experience with beautiful animations, 3D graphics and an integrated AI chatbot for live Q&A.

## 🔗 Live Demo

Check out the next gen AI portfolio: https://ai-portfolio-project.netlify.app/

## ✨ Features

- **Animated Hero Section**: Eye-catching intro with smooth Framer Motion animations.
- **Responsive Design**: Looks great on all devices.
- **3D DNA Model**: Interactive Three.js DNA model rendered with react-three-fiber and drei.
- **AI Chatbot**: Built-in chatbot that answers questions about your portfolio, powered by HuggingFace and Gemini.
- **Resume Summarization**: Uses Gemini API to summarize your resume.
- **Embeddings Storage**: Stores and retrieves embeddings using Supabase.
- **Serverless Backend**: Netlify Functions serve as the backend for AI and embeddings.
- **Animated Sections**: Each section animates into view as you scroll.
- **Skills Radar Charts**: Visualize your technical and soft skills.
- **Projects, Resume, Gallery, FAQ**: All the essentials for a modern portfolio.
- **Dark Mode**: Supports dark and light themes.
- **Custom 404 (Not Found) page**: Directs users back to home.

### 🖼️ Screenshots

<table>
  <tr>
    <td><img src="https://github.com/GiftinTech/images/blob/main/ai-portfolio/ai-portfolio-hero.png?raw=true" alt="Hero section" width="400" height="400"></td>
    <td><img src="https://github.com/GiftinTech/images/blob/main/ai-portfolio/ai-portfolio-chat.png?raw=true" alt="Chatbot view" width="400" height="400"></td>
    <td><img src="https://github.com/GiftinTech/images/blob/main/ai-portfolio/ai-portfolio-about.png?raw=true" alt="About section" width="400" height="400"></td>
    <td><img src="https://github.com/GiftinTech/images/blob/main/ai-portfolio/ai-portfolio-about-education.png?raw=true" alt="About education section" width="400" height="400"></td>
    <td><img src="https://github.com/GiftinTech/images/blob/main/ai-portfolio/ai-portfolio-projects.png?raw=true" alt="Project section" width="400" height="400"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/GiftinTech/images/blob/main/ai-portfolio/ai-portfolio-resume.png?raw=true" alt="Resume section" width="400" height="400"></td>
    <td><img src="https://github.com/GiftinTech/images/blob/main/ai-portfolio/ai-portfolio-gallery.png?raw=true" alt="Gallery section" width="400" height="400"></td>
    <td><img src="https://github.com/GiftinTech/images/blob/main/ai-portfolio/ai-portfolio-contact.png?raw=true" alt="Contact section" width="400" height="400"></td>
    <td><img src="https://github.com/GiftinTech/images/blob/main/ai-portfolio/ai-portfolio-faq.png?raw=true" alt="FAQ section" width="400" height="400"></td>
    <td><img src="https://github.com/GiftinTech/images/blob/main/ai-portfolio/ai-portfolio-404.png?raw=true" alt="404 (Not Found) section" width="400" height="400"></td>
  </tr>
</table>

## 🚀 Tech Stack

- [Vite](https://vitejs.dev/) (build tool)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [Three.js](https://threejs.org/) + [@react-three/fiber](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction) (3D animation in hero and 404)
- [@react-three/drei](https://docs.pmnd.rs/react-three-drei/introduction) (3D animation in hero)
- [Supabase](https://supabase.com/) (for embeddings storage)
- [HuggingFace Inference API](https://huggingface.co/inference-api) (for chatbot)
- [Gemini API](https://ai.google.dev/gemini-api/docs) (for resume summarization)
- [Netlify Functions](https://docs.netlify.com/functions/overview/) (backend serverless functions)
- [EmailJS](https://www.emailjs.com/) (receive and auto-reply to contact messages)
- [Particles.js / tsparticles](https://particles.js.org/) (animated backgrounds)
- [Leaflet](https://leafletjs.com/) (interactive maps)
- [Chart.js](https://www.chartjs.org/) & [react-chartjs-2](https://react-chartjs-2.js.org/) (skills radar chart)
- [clsx](https://github.com/lukeed/clsx) (conditional classNames utility)
- [lucide-react](https://lucide.dev/) (icon library)
- [yup](https://github.com/jquense/yup) & [formik](https://formik.org/) (form validation)
- [typed.js](https://mattboldt.com/demos/typed-js/) (typing effect in hero section)
- [zustand](https://zustand-demo.pmnd.rs/) (state management)
- [marked](https://marked.js.org/) (formatting AI responses)
- [Lazy Loading & Suspense](https://react.dev/reference/react/Suspense) (performance optimization)

### 📁 Project Structure
```
ai-portfolio-projects/
├── netlify/
│ └── functions/
│ ├── embeddings.js
│ ├── chatbot.js
│ └── resume-summary.js
├── public/
│ └── dna3D/
│ └── scene.gltf
├── src/
│ ├── components/
│ │ ├── ui/
│ │ │ ├── Canvas/
│ │ │ │ └── Dna3D.tsx
│ │ │ └── Chatbot.tsx
│ │ ├── Navbar.tsx
│ │ ├── Footer.tsx
│ │ ├── Resume.tsx
│ │ └── ...
│ ├── layouts/
│ │ └── MainLayout.tsx
│ ├── pages/
│ │ ├── HomePage.tsx
│ │ ├── AboutPage.tsx
│ │ ├── ProjectsPage.tsx
│ │ ├── ResumePage.tsx
│ │ ├── GalleryPage.tsx
│ │ ├── FaqPage.tsx
│ │ └── ...
│ └── ...
├── .env
├── .gitignore
├── LICENSE
├── package.json
├── README.md
├── tsconfig.json
└── vite.config.ts
└── ...
```

### 🦋 About the Developer

This project was passionately built by **GiftinTech (Gift Egbonyi)**, a dedicated **AI Frontend Developer**. GiftinTech is always happy to connect, collaborate, and discuss exciting projects with fellow enthusiasts and professionals!

You can find more about their work and connect through:

- **Linktree:** [https://linktr.ee/GiftinTech](https://linktr.ee/GiftinTech)
- **LinkedIn:** [https://www.linkedin.com/in/gift-egbonyi](https://www.linkedin.com/in/gift-egbonyi)
- **Portfolio:** [https://giftegbonyi.vercel.app/](https://giftegbonyi.vercel.app/)

---

[![License: Custom](https://img.shields.io/badge/license-custom-blue.svg)](LICENSE)

---
