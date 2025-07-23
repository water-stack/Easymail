---

# 🎨 EasyMail Landing (Tailwind + HTML)

A clean, responsive landing page built with **HTML** and **Tailwind CSS**, showcasing features like email marketing, contact management, webinar tools, and automated funnels.

---

## 🚀 Features

* Built entirely using **Tailwind CSS** utilities—no custom CSS files.
* Fully **responsive**, designed to scale from mobile to desktop.
* Utilizes **background image** with elegant **overlay** effect and highlighted headings.
* Includes icon/text feature sections for core offerings: email marketing, signup forms, webinars, contact limits, AI website builder, and automated funnels.
* Easily customizable for color schemes, fonts, spacing, and layout.

---

## 🛠️ Getting Started

### Prerequisites

* Node.js and npm installed

### Install & Build

1. Clone the repo:

   ```bash
   git clone https://github.com/water-stack/Easymail.git
   cd Easymail
   ```

2. Install Tailwind CSS:

   ```bash
   npm install
   ```

3. Build CSS (dev/watch mode):

   ```bash
   npx tailwindcss -i ./input.css -o ./output.css --watch
   ```

4. Open `index.html` in your browser to view the landing.

---

## ⚙️ Tailwind Configuration

Your `tailwind.config.js` includes:

* **Purge/content paths** so only used classes are included in production.
* **Extended theme** (if needed) for custom fonts, colors, spacing, etc.
* Optionally configured **plugins** for forms, typography, etc.

---

## 🎨 Customization Tips

* **Change background image** by updating the `bg-[url(...)]` in `index.html`.
* **Adjust overlay** opacity via `bg-white/xx` (e.g., `/50`, `/60`).
* **Modify layout or spacing** using Tailwind’s utility classes like `px-`, `py-`, `grid-cols-`, and responsive breakpoints (`sm:`, `md:`, `lg:`).
* **Icon support**: Use your icon of choice (SVG/FontAwesome) in the feature cards.

---

## 🎯 Deployment

* Copy `index.html` and `output.css` to your server/CDN.
* No build tools required in production—all CSS is pre-generated.
* To optimize file size, add:

  ```bash
  NODE_ENV=production npx tailwindcss -i input.css -o output.css --minify
  ```

---

## 🛡️ Contributing

Contributions are welcome! Here's how:

1. Fork and branch (`git checkout -b feature/my-update`)
2. Make changes in HTML, Tailwind or config files.
3. Test locally.
4. Commit, push, and open a Pull Request.

---

## 📄 License

Published under the **MIT License**. See [LICENSE](./LICENSE) for details.

---
