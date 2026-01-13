# 🏆 Minecraft Advancement Generator

A minimalist, high-performance web application to create custom Minecraft-style achievement (advancement) images. Built with modern web standards and optimized for high-resolution output.

<img width="300" height="70" alt="minecraft-advancement__Custom Achievements!_Star the repo!_" src="https://github.com/user-attachments/assets/bd2a4769-496c-482f-a4e5-1f747edcece5" />

## ✨ Features

*   **High Resolution:** Generates crisp images at **1000x221** pixels, matching the official background quality.
*   **Official Assets:** Uses a comprehensive library of local Minecraft item textures (PNG and WebP).
*   **Searchable Icon Grid:** Quickly find icons through an interactive 5x5 grid with real-time filtering.
*   **Custom Textures:** Don't see the icon you need? Upload your own texture directly from your computer.
*   **Text Customization:**
    *   Separate fields for Top and Bottom text.
    *   Official Minecraft color presets (Yellow, Gold, Red, Aqua, etc.).
    *   Custom HSV/RGB color picker for complete creative freedom.
*   **Dual Themes:** Fully integrated **Dark Mode** (deep black) and **Light Mode** with persistence (saves to local storage).
*   **Vercel Ready:** Pre-configured for instant deployment using Vite and NPM.

## 🚀 Tech Stack

*   **Frontend:** Vanilla JavaScript (ES Modules)
*   **Graphics:** HTML5 Canvas API (High-DPI rendering)
*   **Styles:** Modern CSS3 with Variables (Theme-aware)
*   **Build Tool:** [Vite](https://vitejs.dev/)
*   **Deployment:** Optimized for [Vercel](https://vercel.com/)

## 🛠️ Local Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/AdvancementGenerator.git
    cd AdvancementGenerator
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run in development mode:**
    ```bash
    npm run dev
    ```

4.  **Build for production:**
    ```bash
    npm run build
    ```

## 📂 Project Structure

*   `public/assets/icons2/`: Local directory containing official item sprites.
*   `src/items.js`: Dynamically generated list of available items and extensions.
*   `index.html`: The core application structure and Canvas logic.
*   `styles.css`: Theme-aware styling and responsive layout.

## 🤝 Credits

Developed with ❤️ by:
*   **lFideo**
*   **Snoker**


## ☕ Donate
[![Donation](https://github.com/user-attachments/assets/d7b5fe34-c620-4257-a1cb-190571f00cd4)](https://www.paypal.com/donate/?hosted_button_id=GWVA5XBU7V3GL)



## 📄 License

This project is licensed under the ISC License - feel free to use it for your own projects!

---
*Note: This project is not affiliated with Mojang or Microsoft.*
