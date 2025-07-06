# 🌐 Personal Portfolio Website

This is a responsive **portfolio website** developed using **HTML**, **CSS**, and **JavaScript**, with beautiful animations powered by **Lottie** (Airbnb’s animation library). It showcases your skills, projects, and contact details in a modern and interactive way.

---

## 📸 Demo

> 🔗 [Live Preview](https://your-live-portfolio-link.com)  
> *(Replace with your deployed site link)*

![image](https://github.com/user-attachments/assets/3356184c-9c18-4520-a7b3-9fcad8122539)


---

## 🧰 Tech Stack

- **HTML5** – semantic structure  
- **CSS3** – custom styling and responsiveness  
- **JavaScript** – interactivity (scrolling, navbar, etc.)  
- **Lottie (bodymovin)** – lightweight JSON animations  

---

## 🚀 Features

- ✅ Fully responsive design (mobile-friendly)  
- ✅ Project showcase with cards or sliders  
- ✅ Animated elements using Lottie  
- ✅ Scroll-triggered animations  
- ✅ Simple and clean codebase  
- ✅ Easy to customize for anyone  

---

## 🗂️ Project Structure

```bash
📁 portfolio/
├── index.html           # Main HTML file
├── style.css            # CSS styling
├── script.js            # JavaScript interactivity
├── assets/
│   ├── images/          # Project images
│   └── animations/      # Lottie JSON animation files
└── README.md            # This file
```

---

## 📦 Lottie Integration

To use Lottie animations in your site:

1. **Include the Lottie CDN:**

```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/bodymovin/5.7.4/lottie.min.js"></script>

<div id="lottie-container" style="width:300px; height:300px;"></div>

lottie.loadAnimation({
  container: document.getElementById('lottie-container'),
  renderer: 'svg',
  loop: true,
  autoplay: true,
  path: 'assets/animations/your-animation.json' // Replace with your JSON file
});

```
---

## 📥 Clone Repository
- git clone https://github.com/yourusername/portfolio.git
- cd portfolio


