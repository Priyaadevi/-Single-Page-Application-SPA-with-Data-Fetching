# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
# Single Page Application (SPA) with Data Fetching (React)

This project is a **Single Page Application (SPA)** built with **React**, featuring dynamic data fetching and a responsive UI. It is deployed on **GitHub Pages**.

## 🌐 Live Demo
🔗 [View the Website](http://strong-custard-6522d1.netlify.app)

## 📂 Project Structure
```
/SPA-Data-Fetching
│── public/          # Static assets
│── src/
│   │── components/  # Reusable React components
│   │── App.js       # Main React component
│   │── index.js     # Entry point
│── package.json     # Dependencies and scripts
│── .gitignore       # Git ignore file
│── README.md        # Documentation
```

## 🚀 Features
- **Single Page Application (SPA)** – Uses React Router for navigation.
- **Fetch API Integration** – Retrieves data from an external API dynamically.
- **Responsive Design** – Works on all devices.
- **Deployed on GitHub Pages** – Easy access and hosting.

## 🛠️ Setup & Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Priyaadevi/-Single-Page-Application-SPA-with-Data-Fetching.git
cd -Single-Page-Application-SPA-with-Data-Fetching
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Run the Application Locally
```bash
npm start
```
This will start the development server at `http://localhost:3000/`.

## 🚀 Deployment on GitHub Pages
### 1️⃣ Install GitHub Pages Package
```bash
npm install gh-pages --save-dev
```

### 2️⃣ Update `package.json`
Add the following lines inside `package.json`:
```json
"homepage": "https://priyaadevi.github.io/-Single-Page-Application-SPA-with-Data-Fetching/",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```

### 3️⃣ Deploy the React App
```bash
npm run deploy
```
Your site will be live at:
```text
https://priyaadevi.github.io/-Single-Page-Application-SPA-with-Data-Fetching/ or http://strong-custard-6522d1.netlify.app/
```


## 📝 License
This project is open-source and available under the **MIT License**.


