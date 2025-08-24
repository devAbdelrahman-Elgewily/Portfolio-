# 🚀 Personal Portfolio - AI Developer

A modern, responsive portfolio website built with Next.js 15, React, TypeScript, and Tailwind CSS. Features a hybrid approach with a streamlined main page and dedicated detailed pages.

## ✨ Features

- **Hybrid Architecture**: One-page main experience + dedicated detailed pages
- **Modern Tech Stack**: Next.js 15, React 18, TypeScript, Tailwind CSS
- **Smooth Animations**: Framer Motion for engaging interactions
- **Responsive Design**: Mobile-first approach with desktop enhancements
- **SEO Optimized**: Proper metadata and page structure
- **Fast Performance**: Code splitting and optimized loading
- **Optimized Animations**: Performance-optimized animations with reduced motion support

## 🏗️ Project Structure

```
├── src/
│   ├── app/                 # Next.js app router
│   │   ├── page.tsx        # Main portfolio page
│   │   ├── projects/       # Detailed projects page
│   │   ├── resume/         # Detailed resume page
│   │   └── layout.tsx      # Root layout
│   ├── components/          # Reusable React components
│   ├── hooks/               # Custom React hooks
│   │   └── use-animations.ts # Animation optimization hook
│   ├── lib/                 # Utility functions
│   │   └── animation-utils.ts # Animation performance utilities
│   └── assets/             # Images and static assets
├── docs/                    # Documentation files
│   ├── INDEX.md            # Documentation index
│   ├── README.md           # Detailed project documentation
│   ├── PORTFOLIO_STRUCTURE.md # Architecture explanation
│   ├── SETUP.md            # Setup and configuration guide
│   └── ANIMATION_OPTIMIZATION.md # Animation performance guide
└── public/                  # Static files
```

## 🚀 Quick Start

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Run development server**
   ```bash
   npm run dev
   ```

3. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📚 Documentation

- **[Documentation Index](docs/INDEX.md)** - Navigate all documentation files
- **[Detailed README](docs/README.md)** - Complete project documentation
- **[Portfolio Structure](docs/PORTFOLIO_STRUCTURE.md)** - Architecture and design principles
- **[Setup Guide](docs/SETUP.md)** - Installation and configuration
- **[Animation Optimization](docs/ANIMATION_OPTIMIZATION.md)** - Performance and consistency guide

## 🎯 Key Pages

- **Home** (`/`) - Main portfolio with smooth scrolling sections
- **Projects** (`/projects`) - Detailed project case studies with optimized animations
- **Resume** (`/resume`) - Professional experience and download

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run type-check` - Run TypeScript type checking

## 🎨 Customization

1. **Add your images** to `src/assets/images/`
2. **Update content** in the component files
3. **Customize colors** in `tailwind.config.js`
4. **Add your projects** to the projects arrays
5. **Upload your resume** to the public folder

## 🌟 Tech Stack

- **Framework**: Next.js 15
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion (optimized)
- **Icons**: Lucide React
- **Deployment**: Ready for Vercel/Netlify

## 🎭 Animation Features

- **Performance Optimized**: GPU-accelerated animations with spring physics
- **Reduced Motion Support**: Respects user accessibility preferences
- **Consistent Loading**: Reliable animation triggering across all devices
- **Smooth Interactions**: Optimized hover and tap animations
- **Fallback Support**: Graceful degradation for older browsers

## 📱 Responsive Design

- Mobile-first approach
- Tablet and desktop optimized
- Touch-friendly interactions
- Smooth scrolling navigation

## 🚀 Deployment

This portfolio is ready to deploy to:
- **Vercel** (recommended for Next.js)
- **Netlify**
- **Any static hosting service**

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ using modern web technologies**
