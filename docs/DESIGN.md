# Design System

This document outlines the core aesthetic and functional principles of our design system.

## Brand Identity

### Color Palette
Our color palette is built around a vibrant psychedelic dreamscape creating an ethereal and immersive user experience.
- **Primary Color:** A rich violet, `#8a2be2`, used for calls to action, primary buttons, and key interactive elements.
- **Secondary Color:** A vivid hot pink, `#ff69b4`, for bright, attention-grabbing accents and secondary actions.
- **Tertiary Color:** A turquoise cyan, `#40e0d0`, for highlights and decorative accents.
- **Dream Purple:** A soft lavender, `#d4b3ff`, used throughout the interface for a dreamy quality.
- **Dream Blue:** A soft sky blue, `#a6c8ff`, adding ethereal tones to the palette.
- **Dream Pink:** A gentle rose pink, `#ffb6c1`, for softer backgrounds and surfaces.
- **Mystic Indigo:** A deep indigo, `#2b1b54`, for text and foundational elements.
- **Background Gradient:** A flowing gradient transitioning from dream pink → dream blue → dream purple → light pink (`linear-gradient(120deg, #ffb6c1 0%, #a6c8ff 40%, #d4b3ff 80%, #e0c3fc 100%)`), fixed to viewport for an immersive experience.

### Typography
Our typography system is designed for clarity, hierarchy, and a contemporary aesthetic.
- **Headlines:** Utilize `Epilogue` (weights: 700, 800, 900) for strong, impactful headings with maximum visual presence.
- **Body Text:** `Plus Jakarta Sans` (weights: 400, 500, 600, 700) provides excellent readability for longer passages and general text with a friendly, modern tone.
- **Labels:** `Plus Jakarta Sans` is also used for labels, ensuring consistency and legibility for interactive elements.

## UI Elements

### Roundedness
UI shapes feature generous, organic roundedness to create a soft, dreamy aesthetic.
- **Default:** 3rem (48px) for standard buttons and cards
- **Large:** 5rem (80px) for larger elements and containers
- **Extra Large:** 7rem (112px) for prominent features and accent shapes
- **Organic Shapes:** Apply organic, asymmetrical border-radius patterns (e.g., `50% 50% 40% 60% / 60% 40% 50% 50%`) for flowing, natural-looking decorative elements

### Spacing
Generous spacing is applied throughout the UI, providing ample breathing room between elements for a balanced and comfortable user experience.

## Visual Effects

### Glassmorphism
UI elements utilize a glass-blur effect with:
- 20px backdrop blur
- Semi-transparent white background (`rgba(255, 255, 255, 0.35)`)
- Subtle white border (`rgba(255, 255, 255, 0.4)`) with 2px width

### Animations
- **Floating:** Elements subtly float and rotate with a smooth 8-second ease-in-out cycle, moving up to 30px vertically with gentle 2-degree rotation

### Gradients
- **Dream Gradient Text:** A flowing gradient from primary violet → secondary pink → tertiary cyan, applied as text fill for impactful typography

## Overall Aesthetic
The design system embodies a psychedelic dreamscape—a balance between ethereal, flowing organic shapes and structured, modern UI patterns. The theme emphasizes immersion through fixed gradient backgrounds, floating animations, and glassmorphic elements that create a sense of depth and wonder.