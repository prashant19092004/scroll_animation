# 🎞️ Scroll-Triggered Frame-by-Frame Animation

This project implements a smooth **frame-by-frame scroll animation** using **HTML5 Canvas**, **GSAP (GreenSock Animation Platform)**, **ScrollTrigger**, and **Tailwind CSS**. As you scroll, frames dynamically change to create a seamless animation effect — ideal for creative landing pages, product reveals, or immersive storytelling.

## 🖼️ Demo

👉 [Live Demo (GitHub Pages Link)](https://prashant19092004.github.io/scroll_animation/)

> _Replace the link above with your actual GitHub Pages URL after deployment._

---


---

## 🚀 Technologies Used

- **HTML5 Canvas**
- **Tailwind CSS**
- **GSAP v3** (GreenSock Animation Platform)
- **GSAP ScrollTrigger Plugin**
- **JavaScript (Vanilla)**

---

## 🎮 How It Works

- The canvas displays images (`frame_0001.jpeg` to `frame_0382.jpeg`) loaded from the `/images` folder.
- As the user scrolls through a long scrollable div (`700vh` height), GSAP's ScrollTrigger updates the image shown on canvas.
- Each frame is drawn proportionally to fit the screen using responsive canvas logic.

---

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
