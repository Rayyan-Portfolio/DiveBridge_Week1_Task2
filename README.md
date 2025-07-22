
# DiveBridge_Week1_Task1 – Netflix-Inspired UI

🔗 **Live Preview**: [Visit site](https://dive-bridge-week1-task2.vercel.app/)

This project is a front-end clone of the Netflix landing page interface. It replicates the core layout, background effects, content structure, and styling using only **HTML** and **CSS**, designed as part of Week 1 Task 1 for DiveBridge.

---

## 🛠 Technologies Used

- **HTML5** – for semantic structure and layout  
- **CSS3** – for styling, positioning, flex layout, gradients, and responsiveness  
- **Font Awesome** – for icons such as the language globe  
- **Vercel** – for live deployment and hosting

---

## 📁 Project Structure

```
project-folder/
│
├── index.html                   # Main HTML file
├── README.md                    # Project overview
├── assets/
│   ├── css/
│   │   └── style.css            # All custom styles
│   ├── img/
│   │   ├── logo.png             # Top-left logo
│   │   ├── background.jpg       # Main header background
│   │   ├── tv.png               # Device section
│   │   ├── mobile.jpg           # Mobile preview
│   │   ├── tv-tab-mobile.png    # Tablet & phone preview
│   │   └── children.png         # Kids profile section
```

---

## 🎨 How I Built the UI

### 🧱 HTML

- The layout is broken into **reusable content sections** using `<div class="box">`, each with two halves: image + heading.
- The **header section** contains a background image, logo, language dropdown, sign-in button, and an email bar.
- Background image and gradient are added **directly in the HTML** using the `style` attribute on `.header`.

### 🎨 CSS

- The page is styled using **Flexbox** for all layouts (header, navbar, content boxes).
- Used a **linear-gradient overlay** for a dark transparent effect over the background image.
- Fonts are set to `Arial` and similar sans-serif fallbacks.
- All sections have consistent **padding, borders, and sizing** to mimic Netflix’s brand aesthetic.
- Each `.box` section has alternating layouts (text-image or image-text) and a bottom divider.
- Buttons, inputs, and dropdowns are styled for interaction with `hover` effects and rounded borders.

---

## 📱 Responsiveness

- The UI is flex-based and mobile-friendly.
- Font sizes and sections scale properly on smaller screens.
- The structure is prepared for responsive media queries if needed in future.

---

## 🚀 How to Run Locally

1. Clone this repository or download the ZIP.
2. Make sure all image files are in the `assets/img` directory.
3. Open `index.html` in your browser.

---

## 📌 Future Enhancements

- Add responsive breakpoints for better mobile experience
- Animate sections on scroll (AOS / CSS transitions)
- Add video elements or interactive carousels
- Connect to a backend (for login/signup functionality)

---

## 👨‍💻 Developed By

**Ahmad Rayyan**  
HTML & CSS Developer  
Week 1 Task for DiveBridge
