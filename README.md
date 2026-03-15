# IDR
# Institute of Digital Risk (IDR) Web Platform

A high-performance, responsive web platform designed for the **Institute of Digital Risk**. This project showcases a modern approach to bridging academic theory with technical cyber-risk expertise through an intuitive and professional user interface.

## 🚀 Live Demo
[**View the Live Project Here**](INSERT_YOUR_GITHUB_PAGES_URL_HERE)

---

## 🛠️ Technical Implementation

### 1. Mobile-First Architecture
The site was built using a **Mobile-First** philosophy. Instead of "shrinking" a desktop site, I engineered the layout to stack naturally on mobile devices, ensuring zero horizontal scrolling and perfect legibility.

### 2. Advanced CSS Grid & Flexbox
- **Dynamic Layout:** Implemented a sophisticated 8-column CSS Grid for desktop users, featuring "sticky" sidebar elements that remain visible as the user scrolls through content.
- **Glassmorphism:** Utilized modern UI trends like `backdrop-filter: blur` and subtle orange shadows to create a premium, high-tech aesthetic for the registration forms.

### 3. Responsive Header & Brand Identity
- Custom-built navigation that handles complex brand assets across multiple breakpoints.
- Synchronized branding using a high-contrast palette of **International Orange** and **Deep Black** to project authority and innovation.

## 🧠 Key Challenges & Solutions
- **The "Shift" Problem:** One of the main challenges was transitioning a complex, multi-row grid on desktop into a clean, single-column stack on mobile. I solved this by decoupling the grid logic into specific media queries, allowing for a "fluid" feel regardless of device width.
- **Asset Integration:** Managed dynamic image scaling for the "Cube" icon (Div 8) to ensure it maintained its aspect ratio and alignment next to the Community section.

## 💻 Tech Stack
- **HTML5:** Semantic markup for SEO and accessibility.
- **CSS3:** Custom properties (variables), Grid, Flexbox, and keyframe animations.
- **JavaScript:** Asset management and interactive logic.

---

## 📂 Project Structure
```text
├── index.html     # Main structural document
├── style.css      # Custom modern styling and grid logic
├── assets.js      # Dynamic asset management
└── assets/        # Visual branding (Logos, Hero, Icons)
