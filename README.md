# Communiqué IIT Kharagpur Website

This project is a responsive landing page for **Communiqué**, the official Soft Skills & Personality Development Society of IIT Kharagpur. The website features a theme-switching system (Dark/Light mode), interactive CSS-based sliders, and a fully responsive layout for mobile and desktop.

## 📂 Directory Structure

To ensure the styles and images load correctly, organize your project as follows:

```text
/Project-Root
│
├── index.html              # Main webpage structure
├── styles/                 # All CSS stylesheets
│   ├── main.css            # Global resets and animations
│   ├── navbar.css          # Navigation and theme variables
│   ├── hero.css            # Top landing section styles
│   ├── main_content.css    # Core Competencies section
│   ├── main_content_2.css  # Vision & Mission section
│   ├── governors.css       # Governors slideshow styles
│   ├── FAQs.css            # Interactive FAQ logic
│   ├── contact.css         # Contact form styling
│   └── footer.css          # Footer and social links
└── assets/                 # Images and icons (Reference point)
    ├── icons/              # Social media and UI icons
    └── governors/          # Photos of the society governors

```

---

## 📝 File Overview

### 🏗️ Content (HTML)

* **`index.html`**: The core file that links all styles and defines the website sections, including the navbar, hero section, core competencies, vision/mission, governors, FAQs, and contact footer.

### 🎨 Styling (CSS)

All CSS files are **static** files used to render the visual design and layout.

| File Name | Nature | Description |
| --- | --- | --- |
| **`main.css`** | Static | Sets global typography, background colors, and fade-in scroll animations. |
| **`navbar.css`** | Static | Manages the sticky navbar and the **Dark/Light Mode** CSS variables. |
| **`hero.css`** | Static | Styles the entrance section with a background image and the society branding. |
| **`main_content.css`** | Static | Handles the grid layout for the "Core Competencies" icons and text. |
| **`main_content_2.css`** | Static | Provides layout styles for the Vision and Mission cards. |
| **`governors.css`** | Static | Contains the **CSS animation logic** for the automatic sliding profile section. |
| **`FAQs.css`** | Static | Uses radio-button logic to create an interactive FAQ slider without JavaScript. |
| **`contact.css`** | Static | Styles the user input forms and contact information container. |
| **`footer.css`** | Static | Manages the multi-column footer, social media buttons, and map embed. |

---

## 🚀 How to Open the Website

Since this project uses standard HTML and CSS, you can run it locally without any server installation.

### Method 1: Direct Launch

1. Navigate to your project folder.
2. Find the `index.html` file.
3. **Right-click** `index.html` and select **Open with** > **Google Chrome** (or your preferred browser).

### Method 2: Development Mode (VS Code)

1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension.
3. Click the **"Go Live"** button at the bottom-right corner of the editor.
4. The website will automatically open and refresh whenever you save changes to your code.

