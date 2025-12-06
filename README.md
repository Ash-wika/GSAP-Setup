# GSAP Setup ✨

A smooth, high-performance scrolling starter template powered by **GSAP (GreenSock Animation Platform)** and **Locomotive Scroll**. This project serves as a boilerplate for creating modern, immersive web experiences with scroll-triggered animations.

## 🚀 Features

*   **Locomotive Scroll**: Integrated for that premium, inertia-based smooth scrolling effect.
*   **GSAP ScrollTrigger**: Fully configured to work in sync with Locomotive Scroll (proxy methods engaged).
*   **Responsive Design**: Basic CSS setup ready for scaling.
*   **Modular Code**: Clean `script.js` demonstrating how to hook the two libraries together.

## 🛠️ Tech Stack

*   **HTML5**
*   **CSS3**
*   **JavaScript (ES6+)**
*   **GSAP** (Core + ScrollTrigger)
*   **Locomotive Scroll**

## 📦 Installation

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/Ash-wika/GSAP-Setup.git](https://github.com/Ash-wika/GSAP-Setup.git)
    ```

2.  **Navigate to the project directory**:
    ```bash
    cd GSAP-Setup
    ```

3.  **Install dependencies**:
    ```bash
    npm install
    ```

4.  **Run locally**:
    You can use a simple generic server like **Live Server** (VS Code extension) or run:
    ```bash
    npm run dev
    # (Check package.json for the specific start script if available, usually 'vite' or similar)
    ```

## 🌐 Deployment

This project is hosted live on Render. You can check it out here:

[ **▶️ View Live Demo** ](<https://gsap-setup.onrender.com >) 

## 📝 How it Works

The magic happens in `script.js`, where we:
1.  Initialize **LocomotiveScroll** on the main container.
2.  Update **ScrollTrigger** on every scroll event.
3.  Set up a **ScrollTrigger.scrollerProxy** so GSAP knows how to listen to Locomotive's hijacked scroll events.
4.  Bind everything together to ensure animations fire at the exact right scroll positions.

---
*Created by [Ash-wika](https://github.com/Ash-wika).*
