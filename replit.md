# FlipaClip Animation App

## Overview

FlipaClip is a web-based animation application that provides drawing and animation tools in a browser environment. The application appears to be a single-page web app built with vanilla HTML, CSS, and JavaScript, utilizing Tailwind CSS for styling and Font Awesome for icons. It's designed to be a simplified version of animation software, focusing on frame-based animation creation with drawing tools.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

**Frontend Architecture**
- Single-page application (SPA) built with vanilla HTML, CSS, and JavaScript
- Utilizes Tailwind CSS framework for rapid UI development and responsive design
- Font Awesome integration for consistent iconography
- Google Fonts (Inter) for typography
- CSS custom properties and animations for enhanced user experience
- Mobile-responsive design with touch-friendly interfaces

**UI/UX Design Patterns**
- Tab-based navigation system with smooth transitions
- Modal dialogs for user interactions and settings
- Tool-based interface similar to professional animation software
- Touch-optimized controls for mobile devices
- User selection disabled to prevent accidental text selection during drawing
- Overflow hidden to maintain canvas boundaries

**Drawing and Animation System**
- Canvas-based drawing implementation (implied by the animation app nature)
- Frame-by-frame animation workflow
- Tool selection system for different drawing modes
- Real-time preview capabilities

**Styling Architecture**
- Utility-first CSS approach with Tailwind CSS
- Custom CSS for specific animation behaviors and transitions
- Responsive design principles for cross-device compatibility
- Consistent color scheme and spacing system

## External Dependencies

**CDN-based Libraries**
- Tailwind CSS: Utility-first CSS framework loaded from CDN for styling
- Font Awesome: Icon library (version 6.0.0-beta3) for UI iconography
- Google Fonts: Inter font family for consistent typography across devices

**Browser APIs**
- Canvas API: For drawing and animation rendering
- Touch Events API: For mobile touch interactions
- Local Storage API: Likely used for saving projects and user preferences

**No Backend Dependencies**
- Pure client-side application with no server-side components
- No database connections or API endpoints
- All data processing happens in the browser
- Static hosting compatible