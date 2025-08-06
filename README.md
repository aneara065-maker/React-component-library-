
### 📘 `README.md`

```markdown
# 🌈 React Component Library Demo

This project demonstrates a custom-built component library in React including **Buttons**, **Cards**, and **Modals** using **Tailwind CSS** for styling.

---

## 📁 Project Structure

```

src/
├── components/
│   ├── Button.js
│   ├── Card.js
│   └── Modal.js
├── App.js
├── index.js
└── index.css

````

---

## 🚀 Components Overview

### ✅ Button Component
- Props: `label`, `onClick`, `variant` (`primary`, `secondary`, `success`)
- Colorful and interactive using Tailwind CSS.

### ✅ Card Component
- Displays an image, title, and description.
- Responsive and styled with shadows and spacing.

### ✅ Modal Component
- Appears on clicking the “Success” button.
- Dismissable by clicking outside or pressing the close button.

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/react-component-library.git
cd react-component-library
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the App

```bash
npm start
```

The app should open in your browser at `http://localhost:3000`.

---

## 🎨 Styling with Tailwind CSS

### Tailwind Setup

Make sure your project has Tailwind configured:

```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

Update `tailwind.config.js`:

```js
module.exports = {
  content: ['./src/**/*.{js,jsx}'],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

In `src/index.css`, include:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Import this CSS file in `index.js`.

---

## 📦 Build Your Own Components

You can now extend this library by adding components like:

* Navbar
* Tabs
* Alerts
* Dropdowns

---

## 👩‍💻 Author

**Laiba Javed**
Demo Assignment for React Component Library Development
August 2025

---

## 📸 Preview

![Preview](https://source.unsplash.com/400x300/?react,ui)

---

## 📃 License

This project is for learning and demo purposes. Feel free to modify and reuse.
