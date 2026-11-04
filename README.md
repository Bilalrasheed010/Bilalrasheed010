# 🌐 Bilal Portfolio

Personal developer portfolio built with React, Vite and Three.js, featuring interactive 3D visuals and scroll-driven animation.

🔗 **Live site:** https://bilal-portfolio-bay.vercel.app

![React](https://img.shields.io/badge/React%2019-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white)

## Highlights

- 3D scenes with React Three Fiber and Drei, with fallbacks for devices that can't run them
- GSAP animation and Lenis smooth scrolling
- Content kept in plain data files (`src/data/`: profile, projects, skills, experience, education, socials)
- Reduced-motion and mobile-aware hooks

## Run locally

```bash
npm install
npm run dev      # start the dev server
npm run build    # production build
npm run lint     # lint the code
```

Requires Node.js 20.19 or newer (22 recommended).

## Project structure

```
src/
├── components/   # UI and three/ (3D scenes)
├── sections/     # About, Skills, Projects, Experience, Education, Contact
├── data/         # Portfolio content
├── hooks/        # Reusable hooks
└── styles/       # Theme and micro-interactions
```

## Author

**Muhammad Bilal**: [LinkedIn](https://www.linkedin.com/in/bilal-rasheed-482788252) · [Email](mailto:bilalrasheed1112@gmail.com)
