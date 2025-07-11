# 🌱 Agri Learn

A modern and interactive agricultural learning platform built with React, featuring smooth animations and a responsive design to help users learn about smart farming tools and agricultural growth.

![Agri Learn Banner](./src/images/agrilearn.jpg)

## 📋 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Quick Start](#-quick-start)
- [Installation](#-installation)
- [Available Scripts](#️-available-scripts)
- [Project Structure](#-project-structure)
- [Components Overview](#-components-overview)
- [Key Features](#-key-features-explained)
- [Configuration](#-configuration-files)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [Future Enhancements](#-future-enhancements)
- [License](#-license)
- [Support](#-support)

## ✨ Features

- **🎨 Modern UI/UX**: Beautiful and responsive design with smooth animations
- **⚡ Interactive Components**: Engaging user interface with motion effects
- **📱 Responsive Design**: Mobile-first approach ensuring cross-device compatibility
- **🎬 Smooth Animations**: Framer Motion integration for sophisticated transitions
- **🚀 Performance Optimized**: Fast loading with Vite build tool
- **🧩 Modular Architecture**: Component-based structure for maintainability
- **🌊 Smooth Scrolling**: Locomotive Scroll for enhanced user experience

## 🚀 Tech Stack

| Category | Technology | Version |
|----------|------------|---------|
| **Frontend Framework** | React | 18.3.1 |
| **Build Tool** | Vite | 5.4.10 |
| **Styling** | Tailwind CSS | 3.4.14 |
| **Animations** | Framer Motion | 11.11.17 |
| **Animation Library** | GSAP | 3.12.5 |
| **Smooth Scrolling** | Locomotive Scroll | 5.0.0-beta.21 |
| **Icons** | React Icons | 5.3.0 |
| **Language** | JavaScript | ES6+ |

## ⚡ Quick Start

```bash
# Clone the repository
git clone <repository-url>
cd "frontend code/Agri learn/front"

# Install dependencies
npm install

# Start development server
npm run dev

# Open http://localhost:5173 in your browser
```

## 📦 Installation

### Prerequisites
- Node.js (v16.0.0 or higher)
- npm or yarn package manager

### Step-by-step Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd "frontend code/Agri learn/front"
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

## 🛠️ Available Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build optimized production bundle |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint for code quality checks |

## 📁 Project Structure

```
agri-learn/
├── public/
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── About.jsx          # About section component
│   │   ├── Eyes.jsx           # Interactive eyes component
│   │   ├── Featured.jsx       # Featured content section
│   │   ├── Footer.jsx         # Footer component
│   │   ├── Landingpage.jsx    # Main landing page
│   │   ├── Marque.jsx         # Animated marquee component
│   │   └── Navbar.jsx         # Navigation bar
│   ├── images/
│   │   ├── agrilearn.jpg      # Main banner image
│   │   ├── agrilogo.png       # Application logo
│   │   ├── logo.png           # Secondary logo
│   │   └── videoUrl.mp4       # Background video
│   ├── assets/
│   │   └── react.svg          # React logo
│   ├── App.jsx                # Main application component
│   ├── main.jsx              # Application entry point
│   └── index.css             # Global styles and Tailwind imports
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
├── eslint.config.js
└── README.md
```

## 🎨 Components Overview

### Core Components

| Component | Purpose | Features |
|-----------|---------|----------|
| **Navbar** | Navigation header | Responsive design, smooth transitions |
| **Landingpage** | Hero section | Animated text, branding elements |
| **Marque** | Scrolling animation | Continuous "Agri Learn" text scroll |
| **About** | Platform information | Educational content about agriculture |
| **Eyes** | Interactive element | Engaging animations and user interaction |
| **Featured** | Key highlights | Showcase of important features/content |
| **Footer** | Site footer | Contact information and useful links |

## 🌟 Key Features Explained

### 🎬 Smooth Animations
Powered by **Framer Motion** and **GSAP**:
- Text reveal animations with stagger effects
- Smooth page transitions
- Interactive hover states
- Scroll-triggered animations
- Micro-interactions for enhanced UX

### 📱 Responsive Design
Built with **Tailwind CSS**:
- Mobile-first approach
- Flexible grid systems
- Responsive typography scaling
- Cross-device compatibility
- Touch-friendly interface

### ⚡ Performance Optimization
- **Vite** for lightning-fast development
- Component-based architecture for code splitting
- Lazy loading for images and assets
- Optimized build output
- Modern JavaScript features

### 🌊 Smooth Scrolling
**Locomotive Scroll** integration:
- Hardware-accelerated scrolling
- Parallax effects
- Scroll-based animations
- Enhanced user experience

## 🔧 Configuration Files

| File | Purpose |
|------|---------|
| `vite.config.js` | Vite build and development configuration |
| `tailwind.config.js` | Tailwind CSS customization and theme |
| `postcss.config.js` | PostCSS plugins and processing |
| `eslint.config.js` | Code quality rules and linting setup |

## 🚀 Deployment

### Build for Production

```bash
# Create production build
npm run build

# Preview production build locally
npm run preview
```

### Deployment Platforms

The built application (`dist` folder) can be deployed to:

- **Vercel**: Connect GitHub repository for automatic deployments
- **Netlify**: Drag-and-drop or Git integration
- **GitHub Pages**: Static site hosting
- **Firebase Hosting**: Google's hosting platform
- **AWS S3 + CloudFront**: Scalable cloud hosting

### Environment Variables

Create `.env` file for environment-specific configurations:

```env
VITE_API_URL=your_api_url_here
VITE_APP_NAME=Agri Learn
```

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Getting Started

1. **Fork** the repository
2. **Clone** your fork locally
3. **Create** a feature branch
4. **Make** your changes
5. **Test** thoroughly
6. **Submit** a pull request

### Development Workflow

```bash
# Fork and clone the repo
git clone https://github.com/yourusername/agri-learn.git
cd agri-learn

# Create a feature branch
git checkout -b feature/amazing-feature

# Make your changes and commit
git add .
git commit -m 'Add amazing feature'

# Push to your branch
git push origin feature/amazing-feature

# Open a Pull Request
```

### Code Standards

- Follow ESLint configuration
- Use meaningful commit messages
- Write clean, documented code
- Test your changes thoroughly
- Maintain responsive design principles

## 🎯 Future Enhancements

### Planned Features

- [ ] **User Authentication System**
  - User registration and login
  - Profile management
  - Role-based access control

- [ ] **Interactive Learning Modules**
  - Step-by-step tutorials
  - Interactive quizzes
  - Practical exercises

- [ ] **Progress Tracking**
  - Learning analytics
  - Achievement badges
  - Progress visualization

- [ ] **Multi-language Support**
  - Internationalization (i18n)
  - RTL language support
  - Regional content adaptation

- [ ] **Mobile Application**
  - React Native version
  - Offline functionality
  - Push notifications

- [ ] **Advanced Features**
  - Weather API integration
  - Crop recommendation system
  - Market price tracking
  - Community forum

### Technical Improvements

- [ ] **Performance Enhancements**
  - Image optimization
  - Code splitting optimization
  - CDN integration

- [ ] **Testing**
  - Unit tests with Jest
  - Integration tests
  - E2E testing with Cypress

- [ ] **Accessibility**
  - WCAG 2.1 compliance
  - Screen reader optimization
  - Keyboard navigation

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Agri Learn

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## 📞 Support

### Get Help

- **📧 Email**: support@agrilearn.com
- **🐛 Issues**: [Create an issue](https://github.com/yourusername/agri-learn/issues)
- **💬 Discussions**: [GitHub Discussions](https://github.com/yourusername/agri-learn/discussions)
- **📖 Documentation**: [Wiki](https://github.com/yourusername/agri-learn/wiki)

### Community

- **🌟 Star** this repository if you find it helpful
- **🔄 Share** with the agricultural community
- **🤝 Contribute** to make it better

---

<div align="center">

**Made with ❤️ for the agricultural community**

[🌐 Website](https://agrilearn.com) • [📱 Demo](https://demo.agrilearn.com) • [📚 Docs](https://docs.agrilearn.com)

</div>
