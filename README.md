# mini-link ✂️

> Minimalist, fast and registration-free URL shortener.  
> Built with pure HTML, CSS and JavaScript. No backend, no database.

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-brightgreen?logo=github)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-blue)
![No Backend](https://img.shields.io/badge/backend-none-lightgrey)

---

## ✨ Features

- 🔗 Shorten any URL instantly
- 📋 Copy the short link with one click
- 🕓 History of the last 5 links (saved locally)
- 📱 Responsive — works on mobile and desktop
- 🌙 Automatic dark mode
- ☁️ No own servers — uses the public [is.gd](https://is.gd) API
- ⚡ Zero dependencies — single HTML file
- 🔒 No tracking, no cookies, no signup
- 🌍 Available in 3 languages — 🇦🇷 Spanish · 🇺🇸 English · 🇧🇷 Portuguese

---

## 🚀 Demo

👉 **[mdefatimaperez.github.io/mini-link](https://mdefatimaperez.github.io/mini-link)**

---

## 🛠️ How to use

1. Open the web page
2. Paste any long URL into the text field
3. Click **Shorten URL** (or press `Enter`)
4. Copy the generated short link with the **Copy** button
5. Done! The link works in any browser worldwide

---

## 📦 Local installation

To run the project on your computer:

```bash
# 1. Clone the repository
git clone https://github.com/mdefatimaperez/mini-link

# 2. Enter the folder
cd mini-link

# 3. Open in the browser
# Simply open index.html in your browser
# No server needed, no npm install required
```

---

## 🔌 API

This project uses the public **[is.gd](https://is.gd)** API:
GET https://is.gd/create.php?format=json&url=YOUR_URL

Response:
```json
{ "shorturl": "https://is.gd/abc123" }
```

No API key required. Usage limit: reasonable use per [is.gd terms](https://is.gd/terms.php).

---

## 📄 License

This project is licensed under the **MIT License**.  
Free to use, modify and distribute.

---

> Made with love and a pinch of AI ☕
