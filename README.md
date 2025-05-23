# Vite + React Router DOM

## 🎯 Aim

To create a basic single-page application (SPA) using **React** with **React Router DOM** for client-side routing and **Vite** for fast development and build tooling.

---

## 🛠️ Procedure

1. **Initialize Vite + React Project**
   ```bash
   npm create vite@latest my-vite-app --template react
   cd my-vite-app
   npm install
   ```
2.Install React Router DOM

```bash
npm install react-router-dom
```
3.Set Up Routing

Wrap <App /> in <BrowserRouter> in main.jsx

Use <Routes> and <Route> in App.jsx

Create pages: Home.jsx, About.jsx, Contact.jsx

4.Add Navigation

Use <Link> components for navigation

Style the navigation bar with basic CSS

5.Run the Development Server

```
npm run dev

```


## Output 


![image](https://github.com/user-attachments/assets/a37cd748-4cbd-4a4b-aa8e-43ee2fc175bf)


![image](https://github.com/user-attachments/assets/3cf04403-08c3-4d8e-89ae-08f25344b941)

![image](https://github.com/user-attachments/assets/9a3b1f19-4eae-4753-97a9-d16f52e1ba86)

## Result 
A working React app with three routes:
/ → Home page
/about → About page
/contact → Contact page
Navigation bar to switch between routes
Responsive content rendering without reloading the page

