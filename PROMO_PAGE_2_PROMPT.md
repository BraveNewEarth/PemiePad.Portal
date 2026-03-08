# PermiePad Promo Landing Page 2 - Cinematic Concept & Prompts

## 1. Asset Generation Prompts (Midjourney / DALL-E / Luma / etc.)

Use these prompts in your preferred AI image generator to create the 2D photorealistic assets for the website.

**Asset 1: The Rugged Field Device**
> **Prompt:** A hyper-realistic, high-end product photography shot of a rugged, impact-resistant iPad case sitting on rich, dark topsoil in a shaded forest. The case is industrial, military-grade, with thick protective bumpers in dark charcoal and matte black silicone. The screen of the device is dark but glowing slightly at the edges, reflecting the dense forest canopy above. Sharp focus, cinematic lighting, 8k resolution, photorealistic.

**Asset 2: The Seed (Oak Nut)**
> **Prompt:** Macro photography of a single, perfectly formed oak acorn resting on dark, damp soil. Cinematic studio lighting with a subtle blue rim light and warm key light. Hyper-detailed textures on the ribbed cap and the smooth, polished brown shell of the nut. Photorealistic, shallow depth of field, 8k resolution.

**Asset 3: The Grown Tree**
> **Prompt:** A majestic, fully grown oak tree standing alone in a clearing, shot from a low angle against a dark, moody, overcast sky. The tree is thriving with lush green leaves and thick, structural branches. Cinematic lighting, photorealistic, highly detailed bark and leaf textures, 8k resolution, nature photography.

---

## 2. World-Class Frontend Dev Prompt (React + Framer Motion)

*Copy and paste the below prompt into your code-assistant AI (e.g., v0, Cursor, Claude) to build the production site.*

**[START OF PROMPT]**

Build a high-end, cinematic 2-page digital portfolio and landing page for "PermiePad" using React, Tailwind CSS, and Framer Motion (motion/react). The aesthetic is minimalist, dark-themed (black and deep slate backgrounds, white text), and uses a sophisticated typographic hierarchy to convey "Ecological Intelligence."

**Global Configuration:**
- **Fonts:** Import and use 'Orbitron' or 'Space Grotesk' for massive display headings, 'Inter' or system-ui for body text, and 'JetBrains Mono' for technical/mono elements.
- **Selection:** Custom selection color (canopy green background, white text).
- **Icons:** Use lucide-react (Leaf, Maximize, Zap, ArrowLeft, ArrowRight, Shield).

**Page 1: Hero (Ecological Intelligence)**
- **Background:** Full-screen high-quality looping video of a slow aerial pan over a dense, dark forest canopy. Settings: Muted, playsInline, loop, preload="auto", object-fit cover.
- **Overlays:** Radial vignette on desktop (70% transparent center to 85% black edges) and a heavy bottom-fade gradient on mobile to ensure text legibility.
- **Top Nav:** Left-aligned minimalist 'PermiePad' logo. Right-aligned '1/02' counter with a progress line and a 'Next: AI Engine' button in mono font.
- **Main Content (Left-aligned, mid-screen):**
  - **Large title:** 'PERMIEPAD // ECOLOGICAL INTELLIGENCE' (font-display, uppercase, tracking-tighter, leading-none).
  - **Description:** Light-weight sans text with a max-width of 450px: "Field-ready, offline-first design tool for planetary regeneration. Military-grade reliability for the harshest environments."
- **Technical Specs (Right Column):** A list (Status: Offline-First, Brain: On-Device AI, Scale: Planetary, Casing: Military-Grade) with labels and values separated by thin border-white/20.
- **Bottom Section:**
  - A glass-morphism card (bg-white/5, backdrop-blur-xl, border-white/10) featuring a generated image of the Rugged iPad on Soil. 
  - Project title 'SYS-01: FIELD CAPTURE' and a 'View Details' button.
  - A row of pill-shaped tags (Military-Grade, Offline Sync, iOS) at the bottom right.

**Page 2: Project Details (Permabrain AI Engine)**
- **Background:** Full-screen looping video of subtle data nodes or a dark, moody macro shot of soil and roots.
- **Overlays:** Subtle elliptical vignette to ensure text legibility.
- **Top Nav:** 'Back Home' button with a Lucide ArrowLeft icon.
- **Main Content:**
  - Massive display title on the left: 'PERMABRAIN AI' (leading-[0.85], uppercase).
  - Right-aligned description text: "Elite ecological intelligence driving your design. Instantly cross-reference soil, water, and climate parameters to build robust guilds, right on the device—without a cellular signal." includes a 'Read Specs' link featuring a minimalist underline.
- **Bottom Section:**
  - Two structured info blocks: '01 // OFFLINE INFERENCE' and '02 // ECOLOGICAL GUILDS' with uppercase mono subtext elaborating on the local-first AI capabilities.
  - Navigation arrows (Left/Right) in circular borders and a meta-info block (Offline Mode | CoreML) with an italicized caption.

**Interactions & Responsiveness:**
- Use `AnimatePresence` from Framer Motion for smooth opacity and subtle slide exit/enter transitions between these two pages.
- Implement entrance animations for text and cards (fade in from y-offset: 20px, staggered).
- On mobile: The video should occupy the top half (h-[50vh]) with a smooth, aggressive gradient transition to the dark solid background content below to keep text readable.

**Technical Note for Implementation:**
Ensure your `App.tsx` manages a simple state toggle between these two views (`HeroPage` and `DetailPage`) and that components are imported and rendered within an `AnimatePresence` block to maintain the "cinematic" and fluid app-like feel. Do not use placeholders for the core styling logic or Framer Motion variants. Output complete, working code.

**[END OF PROMPT]**
