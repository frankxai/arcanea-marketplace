---
name: arcanea-design
description: Arcanea design system with glassmorphic components and consciousness-aligned aesthetics
---

# Arcanea Design System
## Premium UI for Conscious Creators

The Arcanea design system combines glassmorphism, cosmic gradients, and sacred geometry for interfaces that feel both futuristic and deeply human.

## Design Principles

### 1. Depth Through Transparency
Glassmorphic layers create spatial depth, suggesting the layered nature of consciousness and creation.

### 2. Cosmic Color Language
Aurora gradients and celestial tones evoke the infinite creative space.

### 3. Sacred Geometry Accents
Subtle geometric patterns reference universal harmonics.

### 4. Organic Flow
Fluid animations and curved forms soften technical precision.

## Color System

```css
/* Primary Palette */
--arcanea-purple: #8B5CF6;
--arcanea-cyan: #06B6D4;
--arcanea-gold: #F59E0B;

/* Backgrounds */
--void: #0F0F1A;
--cosmos: #1A1A2E;
--nebula: #16213E;

/* Accents */
--starlight: #E2E8F0;
--aurora-1: rgba(139, 92, 246, 0.3);
--aurora-2: rgba(6, 182, 212, 0.3);
```

## Component Library

### Glass Card
```css
.glass-card {
  background: linear-gradient(
    135deg,
    rgba(255, 255, 255, 0.1) 0%,
    rgba(255, 255, 255, 0.05) 100%
  );
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.18);
  border-radius: 16px;
}
```

### Cosmic Button
```css
.cosmic-button {
  background: linear-gradient(135deg, #8B5CF6, #06B6D4);
  border: none;
  border-radius: 12px;
  padding: 12px 24px;
  color: white;
  font-weight: 600;
  box-shadow: 0 4px 15px rgba(139, 92, 246, 0.4);
  transition: transform 0.2s, box-shadow 0.2s;
}

.cosmic-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(139, 92, 246, 0.5);
}
```

### Aurora Background
```css
.aurora-bg {
  background: 
    radial-gradient(circle at 20% 20%, rgba(139, 92, 246, 0.15), transparent 50%),
    radial-gradient(circle at 80% 80%, rgba(6, 182, 212, 0.15), transparent 50%),
    #0F0F1A;
}
```

## Typography

```css
/* Headings */
font-family: 'Poppins', sans-serif;
font-weight: 600;

/* Body */
font-family: 'Inter', sans-serif;
font-weight: 400;

/* Code */
font-family: 'JetBrains Mono', monospace;
```

## Animation Patterns

### Gentle Float
```css
@keyframes float {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-10px); }
}
```

### Pulse Glow
```css
@keyframes pulse-glow {
  0%, 100% { box-shadow: 0 0 20px rgba(139, 92, 246, 0.3); }
  50% { box-shadow: 0 0 40px rgba(139, 92, 246, 0.6); }
}
```
