# 🌐 Global Corporate UI – Responsive Theme with Dark Mode

A modern and professional responsive UI built with HTML, CSS, and JavaScript. Designed for enterprise-level applications, this interface includes a sleek dark mode toggle, semantic structure, and a scalable design system using CSS variables.

## ✨ Features

- 🎨 **Light and Dark Mode** toggle with smooth transitions  
- ⚙️ **CSS Variables** for easy theming and maintainability  
- 🧱 **Reusable Components** like Hero, Footer, and Header  
- 💡 **Clean and Accessible Typography**  
- 📱 **Fully Responsive** for mobile and desktop layouts  
- 🌍 **Scalable for Global Applications**

---

## 📸 Preview

![Preview](/preview.png) 
![Preview](./preview2.png)
![Preview](./preview3.png)
![Preview](./preview4.png)   

---

## 🚀 Technologies

- HTML5
- CSS3 (custom properties, media queries)
- JavaScript (vanilla)

---

## 📁 File Structure

/project-root
│
├── index.html
├── style.css
├── script.js
└── assets/
└── images/

pgsql
Copiar
Editar

---

## 🔄 Theme Toggle

The dark mode toggle updates the UI in real time by toggling the `.dark` class on the `<body>` element. Colors are managed with CSS custom properties (`--var`) for clarity and control.

```js
const toggleButton = document.getElementById('theme-toggle');
toggleButton.addEventListener('click', () => {
  document.body.classList.toggle('dark');
});
🛠 Customization
To adjust colors, simply modify the CSS variables in the :root and body.dark blocks:

css
Copiar
Editar
:root {
  --background-color: #f7f7f7;
  --text-color: #2a2a72;
  --accent-color: #9e01dc;
  ...
}

body.dark {
  --background-color: #121212;
  --text-color: #ffffff;
  --accent-color: #c84bff;
  ...
}
📌 Best Practices Applied
Semantic HTML structure

Smooth CSS transitions

Mobile-first responsive design

Clear class naming and BEM-inspired style

Readable and scalable color system

🧩 Future Improvements
Save theme preferences using localStorage

Add ARIA support for accessibility

Componentize with React or Web Components

Internationalization (i18n) support

