# **Project Blueprint: MaracatuTech Landing Page**

## **1. Overview**

This document outlines the design, features, and implementation plan for the MaracatuTech landing page. The goal is to create a visually stunning, modern, and informative single-page website for a fictional tech event that merges technology with the vibrant culture of Maracatu.

## **2. Design & Style Guide**

- **Aesthetic:** A bold, energetic, and premium feel that blends cultural vibrancy with a dark, tech-focused theme.
- **Color Palette:**
  - **Primary Background:** A very dark grey (`#121212`) with a subtle noise texture to add a tactile feel.
  - **Accent Colors:** Vibrant, contrasting colors inspired by Maracatu costumes for interactive elements, headlines, and highlights. We'll use `oklch` for more vivid colors: `oklch(70% 0.25 290)` (a vivid magenta), `oklch(80% 0.2 145)` (a bright cyan-green).
  - **Text:** Off-white (`#EAEAEA`) for body text, with accent colors for key headlines.
- **Typography:**
  - **Headlines:** An expressive, bold, and slightly wide font to grab attention.
  - **Body:** A clean, highly readable sans-serif font for paragraphs and details.
- **Visual Effects:**
  - **Drop Shadows:** Multi-layered, soft drop shadows on cards and key UI elements to create a sense of depth and a "lifted" appearance.
  - **Glow Effect:** Interactive elements like buttons will have a subtle, colored `box-shadow` to create a "glow" effect on hover and focus.
- **Layout:** A responsive, single-column layout for mobile that expands to a more complex grid on larger screens. The design will be centered and have ample white space to feel clean and balanced.
- **Iconography:** Modern, clean icons for navigation and social media links.

## **3. Features & Sections**

- **Header & Navigation:** A sticky header containing the event logo ("MaracatuTech") and navigation links that smoothly scroll to the corresponding sections.
- **Hero Section:**
  - A large, impactful headline with the event name.
  - A catchy tagline: "Where Rhythm Meets a New Algorithm."
  - A prominent Call-to-Action (CTA) button: "Register Now".
  - A background image placeholder that visually merges themes of music/culture and technology.
- **Speakers Section:**
  - A grid of "speaker cards."
  - Each card will feature a placeholder image, the speaker's name, and their title.
  - The cards will have the "lifted" drop shadow effect.
- **Footer:** Simple footer with social media links and copyright information.

## **4. Implementation Plan (Current Request)**

1.  **HTML (`index.html`):**
    *   Set up the main document structure with `<header>`, `<main>`, and `<footer>`.
    *   Create the hero section with a `div` and placeholder text/button.
    *   Add a section for "Speakers" with placeholder card `div`s.
    *   Link to Google Fonts for the chosen typography.
    *   Link the `style.css` and `main.js` files.

2.  **CSS (`style.css`):**
    *   Define CSS variables for the color palette, fonts, and shadows.
    *   Apply the background texture to the `body`.
    *   Style the hero section, including the headline, tagline, and the glowing CTA button.
    *   Implement the speaker card style with the multi-layered drop shadow.
    *   Add responsive design rules using media queries to ensure the layout adapts to different screen sizes.
    *   Style the header and footer.

3.  **JavaScript (`main.js`):**
    *   (Initially empty) Will be used later to add interactivity like smooth scrolling or dynamic content loading if needed. For this initial version, we will focus on the static page structure and styling.
