# PermiePad Promo Landing Page - Concept & Prompt

## 1. Landing Page Copy (Investor Pitch)

**Hero Headline:**
Design from the Soil Up

**Sub-headline:**
Ecological Intelligence. Ruggedized for the Field.

**Scroll Section 1: Built for the Elements**
**Headline:** Field-Ready. Offline-First.
**Body:** Military-grade reliability for the harshest environments. Your ecological data stays safe, synced whenever connectivity returns. No signal? No problem.

**Scroll Section 2: On-Device Intelligence**
**Headline:** Permabrain AI
**Body:** Elite ecological intelligence driving your design. Instantly cross-reference soil, water, and climate parameters to build robust guilds, right on the device.

**Scroll Section 3: The Future of the Land**
**Headline:** Visualizing Tomorrow
**Body:** From degraded land to thriving ecosystems. See the precise workflow from initial observation to complete implementation.

---

## 2. World-Class 3D Dev Prompt

*Copy and paste the below prompt into your website builder AI (e.g., v0, Cursor, Claude) or hand it to a 3D technical artist/frontend developer.*

**[START OF PROMPT]**

Act as a world-class Creative Frontend Developer and 3D Technical Artist. Your objective is to write the complete, production-ready code for a cutting-edge 3D landing page that will render flawlessly inside a web canvas preview. This landing page is to promote the concept of "PermiePad" to investors.

**TECH STACK AND SETUP**
Use HTML5, CSS3, Vanilla JavaScript, Tailwind CSS via CDN for the UI overlay, Three.js via CDN for the 3D environment, and GSAP via CDN for smooth scroll animations. Output everything into a single unified index.html block containing the inline CSS, the HTML structure, and the JavaScript logic.

**NARRATIVE & COPY**
The UI overlay must feature minimal but impactful text to pitch the concept to investors.
- Hero Headline: Design from the Soil Up
- Sub-headline: Ecological Intelligence. Ruggedized for the Field.
- Block 1: "Field-Ready. Offline-First." -> Military-grade reliability for the harshest environments. Your ecological data stays safe, synced whenever connectivity returns. No signal? No problem.
- Block 2: "Permabrain AI" -> Elite ecological intelligence driving your design. Instantly cross-reference soil, water, and climate parameters to build robust guilds, right on the device.
- Block 3: "Visualizing Tomorrow" -> From degraded land to thriving ecosystems. See the precise workflow from initial observation to complete implementation.

**THE 3D SCENE AND AESTHETIC**
The theme is Dark Mode Cyber-Minimalism. The background should be a deep, rich dark gradient from almost black to very dark charcoal. 

*CRITICAL SPECIFICATION*: Do not use basic Three.js geometric primitives (boxes, cylinders, spheres) to emulate objects. You must configure the scene to load **photorealistic** high-quality 3D assets (GLTF/GLB models or high-end procedural shaders). The 3D scene must feature:
1. A photorealistic iPad with a Military Grade Rugged Protective Design cover on the back side. 
2. A photorealistic Oak Nut (seed).
3. A photorealistic, detailed Oak Tree.

**CAMERAS, PHYSICS, AND SCROLL ANIMATION (GSAP + Three.js)**
Sequence of exact events tied to the user's scroll progress:
1. The photorealistic iPad rotates 360 degrees in an animation showing off the rugged protective cover on the back.
2. The iPad then lays down completely flat.
3. The photorealistic Oak Nut (seed) is superimposed, animating in as if it is sitting directly on top of the iPad screen.
4. As the user continues to scroll down, the iPad moves parallax-downwards visually, while a photorealistic tree starts to emerge and grow from the nut.
5. Tree Growth sequence: First the tree trunk emerges and grows, followed by tree limbs branching out, and finally, a canopy of leaves blossoms.
6. Once the tree has fully grown, the user scrolls further down under the iPad to reveal the 2D UI elements.

**FRONTEND UI AND 2D GALLERY COMPOSITION**
Below the 3D canvas sequence, the page flows into a gallery. Ensure the precise order of content as the user scrolls:
1. Image 1: Prototype Screen 1 (Use placeholder image class or src)
2. Video 1: Promo Video (Use placeholder video src)
3. Image 2: Prototype Screen 2
4. Image 3: Prototype Screen 3
5. Image 4: Prototype Screen 4
6. Video 2: Promo Video
7. Image 5: Prototype Screen 5

**UI STYLING RULES**
Overlay the 3D canvas with a fixed-position HTML layer using Tailwind. Features massive, bold sans-serif typography. Use `backdrop-blur` glassmorphism for all content cards so the 3D background remains visible behind the text.

**STRICT EXECUTION RULES**
Write the complete, working code. Do not use placeholders for the core GSAP logic, Three.js setup, or lighting configs. Ensure the canvas resizes dynamically using window resize event listeners. Make the Tailwind UI mobile-friendly. Enable antialiasing on the WebGLRenderer and set the pixel ratio properly for high-resolution displays. Generate the complete self-contained code now.

**[END OF PROMPT]**
