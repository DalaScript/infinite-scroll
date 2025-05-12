
# 📸 Unsplash Infinite Scroll Gallery

This is a **dynamic image gallery** built with **HTML, CSS, and JavaScript** that uses the **Unsplash API** to fetch and display random images with **infinite scrolling**. When the user scrolls near the bottom of the page, more photos are automatically loaded.

> ⚠️ **Important:** You must use your own **Unsplash API key** to make this project work. Visit [Unsplash Developers](https://unsplash.com/developers) to register and obtain an API key.

---

## Table of contents

- [📚 Overview](#-overview)
  - [🧠 How It Works](#-how-it-works)
  - [🖼️ Screenshot](#️-screenshot)
  - [📌 Features](#-features)
- [📦 Setup & Installation](#-setup--installation)
  - [**1️⃣ Clone the Repository**](#1️⃣-clone-the-repository)
  - [**2️⃣ Add Your API Key**](#2️⃣-add-your-api-key)
  - [**3️⃣ Run the Project**](#3️⃣-run-the-project)
- [📈 My process](#-my-process)
  - [🛠️ Built with](#️-built-with)
  - [➡️ Continued development](#️-continued-development)
- [👤 Author](#-author)
  - [🌐 Connect with Me](#-Connect-with-Me)
  - [💻 Coding Profiles](#-Coding-Profiles)

---

## 📚 Overview

### 🧠 How It Works

1. On page load, the app fetches a few images from the Unsplash API.
2. Images are added dynamically to the DOM.
3. When the user scrolls near the bottom, a new batch of images is fetched and displayed.
4. The number of images fetched increases after the initial load for better performance.

### 🖼️ screenshot

![](./assets/screenshot.jpg)

### 📌 Features
- ✅ Infinite Scroll to fetch more images on demand
- ✅ Responsive layout for both desktop and mobile
- ✅ Smooth image loading experience
- ✅ Styled with custom fonts and media queries

---

## 📦 Setup & Installation

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/unsplash-infinite-scroll.git
cd unsplash-infinite-scroll
```

### **2️⃣ Add Your API Key**
Replace the `apiKey` in `script.js` with **your own Unsplash API key**:
```js
const apiKey = 'YOUR_UNSPLASH_API_KEY';
```

### **3️⃣ Run the Project**
You can open `index.html` directly in your browser or use a local development server:
```bash
# Example: Using VS Code Live Server or any static file server
```

---

## 📈 My process

### 🛠️ Built with
- **HTML5**
- **CSS3** (Media Queries + Google Fonts)
- **Vanilla JavaScript**
- **Unsplash API**

### ➡️ Continued development

According to this course, the next project will be 'Picture in Picture'.

---

## 👤 Author

### 🌐 Connect with Me

- [Instagram](https://www.instagram.com/DalaScript)
- [YouTube](https://www.youtube.com/@DalaScript)

### 💻 Coding Profiles

- [freeCodeCamp](https://www.freecodecamp.org/DalaScript)
- [FrontendMentor](https://www.frontendmentor.io/profile/DalaScript)
- [GitHub](https://github.com/DalaScript)
