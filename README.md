# HEC Pharm 3D Interactive Webpage Showcase

> **Note**: This is a showcase repository. The source code is proprietary and protected under NDA. This repository demonstrates the project's features, architecture, and outcomes without exposing confidential code.

<div align="center">
  <img src="assets/logo-placeholder.png" alt="HEC Pharm Logo" width="200"/>
  
  ### 🧬 Next-Generation Pharmaceutical Webpage
  
  [![Next.js](https://img.shields.io/badge/Next.js-15.3-black?style=flat-square&logo=next.js)](https://nextjs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
  [![Three.js](https://img.shields.io/badge/Three.js-r176-black?style=flat-square&logo=three.js)](https://threejs.org/)
  [![Status](https://img.shields.io/badge/Status-Production-success?style=flat-square)]()
</div>

---

## 🎯 Project Overview

Developed an enterprise-grade interactive webpage for HEC Pharm USA, revolutionizing how medical professionals interact with pharmaceutical data through cutting-edge 3D visualizations and immersive user experiences.

### 🎭 The Challenge

HEC Pharm needed a modern web platform that could:
- Present complex molecular data in an intuitive, interactive format
- Engage medical professionals with immersive 3D visualizations
- Maintain enterprise-level security and performance

### 💡 The Solution

Built a full-stack application leveraging the latest web technologies to create an unparalleled user experience combining scientific accuracy with stunning visuals.

---

## ✨ Key Features

### 🌍 Interactive 3D Globe
- Real-time data visualization on a rotating globe
- Smooth camera controls and animations
- Custom markers and heat maps

### 🧪 Molecular Visualization
- 3D molecular structure rendering
- Interactive rotation and zoom
- Real-time property calculations
- Educational annotations

### 📊 Dynamic Dashboards
- Live data updates
- Customizable widgets
- Advanced filtering and search

### 🎬 Multimedia Integration
- Imemersive videos
- Interactive tutorials
- 3D interactive objects
- Mobile-first approach

---

## 🛠️ Technical Architecture

### Frontend Stack
```
├── Framework: Next.js 15.3.1 (App Router)
├── Language: TypeScript 5
├── 3D Graphics: Three.js + React Three Fiber + Drei
├── Animations: Framer Motion 12.9
├── Styling: Tailwind CSS 4.1.4
├── State Management: React Hooks + Context
└── Build Tool: Turbopack
```

### Key Dependencies
- **@react-three/fiber**: React renderer for Three.js
- **@react-three/drei**: Useful helpers for React Three Fiber
- **framer-motion**: Production-ready animation library
- **three-globe**: 3D globe visualization
- **@emailjs/browser**: Email integration
- **react-player**: Video player component

### Performance Optimizations
- Lazy loading for 3D models
- Texture compression and optimization
- Code splitting and dynamic imports
- Service worker caching
- CDN asset delivery

---

## 📸 Screenshots

<div align="center">
  <h3>🏠 Immersive Landing Heros</h3>
  <img src="screenshots/section-hero.png" alt="Landing Page" width="400"/>
  <img src="screenshots/section-careers.png" alt="Landing Page" width="400"/>
  <!-- <p><em>Immersive landing heros</em></p> -->
</div>

<div align="center">
  <h3>🌍 3D Interactive Objects</h3>
  <img src="screenshots/section-footprint.png" alt="3D Globe Demo" width="400"/>
  <img src="screenshots/section-global-layout.png" alt="Analytics Dashboard" width="400"/>
  <!-- <p><em>Real-time global pharmaceutical data visualization</em></p> -->
</div>

<div align="center">
  <h3>🧬 Molecular Blocks</h3>
  <img src="screenshots/section-ecosystem.png" alt="Molecular Visualization" width="400"/>
  <img src="screenshots/section-factories.png" alt="Molecular Visualization" width="400"/>
  <!-- <p><em>Interactive 3D molecular structure exploration</em></p> -->
</div>

<div align="center">
  <h3>📱 Live Statistics</h3>
  <img src="screenshots/section-about.png" alt="Mobile View" width="400"/>
  <img src="screenshots/section-statistics.png" alt="Mobile View" width="400"/>
  <!-- <p><em>Fully responsive design optimized for all devices</em></p> -->
</div>

<div align="center">
  <h3>📊 Searchable Products List</h3>
  <img src="screenshots/section-product.png" alt="Mobile View" width="800"/>
  <!-- <p><em>Comprehensive data analytics and reporting</em></p> -->
</div>

---

## 🔧 Technical Highlights

### Advanced 3D Implementation
```typescript
// Example of optimized 3D rendering approach
const MoleculeViewer = () => {
  // Efficient geometry instancing
  // LOD (Level of Detail) implementation
  // Custom shader materials
  // Optimized render loops
}
```

### Performance Optimization Strategies
- Implemented custom WebGL optimizations
- Used geometry instancing for repeated elements
- Developed efficient frustum culling system
- Created progressive loading for 3D assets

### Security Measures
- End-to-end encryption for sensitive data
- OWASP compliance
- Regular security audits
- Protected API endpoints

---

<div align="center">
  <sub>Built with ❤️ using Next.js, Three.js, and modern web technologies</sub>
</div>

---

**⚠️ Confidentiality Notice**: This showcase represents work performed under NDA. All code, specific implementation details, and proprietary information remain confidential. Screenshots and descriptions have been approved for public display.
