# Sanjai - Ultra-Premium Cinematic Motion Graphics Portfolio

An ultra-premium, cinematic motion graphics portfolio website for Motion Designer & Video Editor **Sanjai**. Built as an interactive experience that feels like a motion reel, not a traditional portfolio.

## 🎬 Overview

This portfolio website reimagines what a motion designer's online presence should be. Instead of traditional cards and layouts, every scroll feels like a new scene in a film. The site prioritizes:

- **Motion & Typography** - Kinetic animations, flowing transitions, and dynamic text reveals
- **Cinematic Aesthetic** - Dark, high-contrast design with neon accents
- **Storytelling** - Five narrative scenes that unfold the creator's vision, craft, work, tools, and experience
- **Emotional Impact** - Smooth pacing, timing, and visual rhythm throughout

## ✨ Features

### 🎯 Five Cinematic Scenes

1. **Hero (Opening Scene)** - Full-screen kinetic typography "Turning ideas into motion"
2. **Vision (The Story)** - Animated statements revealing the creator's artistic philosophy
3. **Craft (The Skills)** - Full-screen skill cards as motion graphics title sequences
4. **Work (The Reel)** - Dynamic project showcase with hover interactions
5. **Tools (The Arsenal)** - Minimalist software expertise with animated progress
6. **Resume (The Background)** - Interactive timeline with experience and education
7. **Footer (The Connection)** - Contact info and social links with smooth animations

### 🎨 Design Highlights

- **Dark Cinematic Background** - `#0a0a0a` to `#1a1a1a` gradient
- **Neon Accents** - Cyan (`#00ffff`), Electric Blue (`#0080ff`), Violet (`#c400ff`)
- **Stroke + Fill Text** - CSS text-stroke for artistic typography
- **Smooth Animations** - Framer Motion for sophisticated motion control
- **Responsive Design** - Mobile-first approach, fully responsive
- **No Generic UI** - No cards, boxes, or traditional layouts

### 🚀 Technical Stack

- **Framework** - Next.js 14 (App Router)
- **Styling** - Tailwind CSS
- **Animations** - Framer Motion
- **Language** - TypeScript
- **Font** - Inter (Google Fonts)

## 📦 Installation

### Prerequisites
- Node.js 16.x or higher
- npm or yarn

### Setup

1. **Clone or navigate to the project**
```bash
cd NEXTJS-portflio-main
```

2. **Install dependencies**
```bash
npm install
```

3. **Run development server**
```bash
npm run dev
```

4. **Open in browser**
```
http://localhost:3000
```

## 🛠️ Development

### Build for production
```bash
npm run build
npm start
```

### Run linter
```bash
npm run lint
```

## 📝 Customization Guide

### Update Projects
Edit `src/components/Work.tsx` - Modify the `projects` array with your work:

```typescript
const projects: Project[] = [
  {
    id: 1,
    title: "Your Project Title",
    category: "Motion Design",
    description: "Project description here",
    tools: ["After Effects", "Blender"],
    year: 2024,
  },
  // Add more projects...
];
```

### Update Experience
Edit `src/components/Resume.tsx` - Modify the `experience` array:

```typescript
const experience: ExperienceItem[] = [
  {
    period: "2023 - Present",
    role: "Your Role",
    company: "Company Name",
    description: "Your description",
  },
  // Add more experience...
];
```

### Update Tools/Skills
Edit `src/components/Tools.tsx` - Modify the `tools` array:

```typescript
const tools: Tool[] = [
  { name: "After Effects", category: "primary", level: 100 },
  { name: "Your Software", category: "primary", level: 90 },
  // Add more tools...
];
```

### Customize Colors
Edit `tailwind.config.ts` to change the neon accent colors:

```typescript
colors: {
  neon: {
    cyan: "#00ffff",
    blue: "#0080ff",
    violet: "#c400ff",
  },
}
```

### Update Personal Info
- **Site Title** - Edit `src/app/layout.tsx`
- **Contact Email** - Update in `src/components/Navbar.tsx` and `src/components/Resume.tsx`
- **Social Links** - Update in `src/components/Footer.tsx`

## 📱 Responsiveness

The site is built mobile-first and fully responsive:
- **Mobile** - Optimized single-column layout
- **Tablet** - Two-column grids where appropriate
- **Desktop** - Full multi-column layouts with hover effects

## 🎬 Animation Framework

All animations use **Framer Motion** with:
- Scroll-based reveals using `useInView` hook
- Smooth transitions and easing
- Interactive hover states
- Staggered animations for visual interest

## 📊 Performance Optimization

- Next.js 14 with automatic code splitting
- Optimized images and assets
- CSS animations for smooth 60fps performance
- Lazy loading of components
- SEO-friendly structure

## 🔗 Deployment

### Deploy to Vercel (Recommended)
```bash
npm install -g vercel
vercel
```

### Deploy to Other Platforms
- **Netlify** - Connect GitHub repo and deploy
- **AWS Amplify** - Follow AWS deployment guide
- **Self-hosted** - Run `npm run build` and serve `out` directory

## 📄 License

This portfolio template is created for Sanjai and is customizable for personal use.

## 🤝 Support

For customization help or questions, refer to:
- [Next.js Documentation](https://nextjs.org/docs)
- [Framer Motion Docs](https://www.framer.com/motion/)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)

---

**Built with ❤️ for creative storytelling through motion**
