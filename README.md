# 🌹 Hwa Ryun: The Red-Haired Guide

A high-performance, visually striking landing page and **interactive AI experience** dedicated to **Hwa Ryun**, the enigmatic strategist from the *Tower of God* series. This project showcases a modern "Dark Crimson" UI/UX design, smooth animations, a responsive layout, and a fully integrated AI chatbot that roleplays as the Red Witch herself.

![Project Preview](ss.png)

## ✨ Features
* **🤖 Intelligent AI "Guide" Chatbot:** An integrated AI assistant powered by GPT-4o (via GitHub Models). She speaks in character, parses Markdown for rich text formatting, and features dynamic "Online/Offline" status handling if the Tower's connection (API) is lost.
* **Custom Crimson Theme:** A curated color palette designed specifically to match Hwa Ryun's aesthetic and FUG affiliation.
* **Interactive Gallery:** A sleek image grid with hover effects and a built-in Lightbox for high-res viewing.
* **Smooth Motion:** Custom Tailwind animations including floating elements, fade-in-on-scroll, and glow effects.
* **Fully Responsive:** Optimized for desktop, tablet, and mobile viewing.
* **Background Ambience:** Integrated music controller with a custom UI toggle.
* **Glassmorphism:** Modern blurred-background navigation and profile cards.
* **🛠️ Advanced Developer Tools:** Includes a cross-domain iframe DOM highlighting script for element inspection and tracking.

## 🛠️ Tech Stack
* **HTML5 & CSS3:** Semantic structure and custom keyframe styling.
* **Tailwind CSS:** For the utility-first styling, typography plugin, and responsive grid system.
* **JavaScript (Vanilla):** Logic for the AI chatbot, music player, image lightbox, and scroll observer animations.
* **AI Integration:** Fetch API securely interacting with the GitHub Models inference endpoints.
* **Marked.js:** Lightweight library for parsing the AI's Markdown output into HTML.
* **Google Fonts:** Utilizing 'Poppins' for a clean, modern look.

## 🚀 Quick Start
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/hwa-ryun-web.git](https://github.com/YourUsername/hwa-ryun-web.git)
    cd hwa-ryun-web
    ```
2.  **Configure the AI Assistant:**
    To use the Hwa Ryun chatbot, open `index.html` and replace the placeholder token in the JavaScript section with your own GitHub Personal Access Token (PAT):
    ```javascript
    const GITHUB_TOKEN = "YOUR_ACTUAL_GITHUB_TOKEN_HERE"; 
    ```
    *(Note: For production, use a backend proxy to hide this key!)*
3.  **Open the project:**
    Simply open `index.html` in your favorite browser.

## 📸 Screenshots
| Profile Section | Image Gallery |
| :--- | :--- |
| ![Profile](profile.png) | ![Gallery](ssgaleri.png) |

## 🎨 Design Philosophy
The goal of this project was to move away from generic anime fan pages. Every element—from the particle background to the specific "S-Rank" stat cards and the carefully prompted AI persona—was designed to reflect Hwa Ryun's status as a master strategist. Even the error handling remains in character, ensuring the immersion of the Tower is never broken.

---
*Created with ❤️ for the Tower of God community.*