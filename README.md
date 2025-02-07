# 🌀 Learn React Basics  

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" width="100" alt="React Logo">
</p>

Welcome to the **Learn React Basics** repository! 🚀 This repo helps you quickly understand React fundamentals and start building web apps.  

## 📌 What You'll Learn  
✅ Components, JSX, Props, and State  
✅ Handling events and forms  
✅ React Hooks (`useState`, `useEffect`)  
✅ React Router for navigation  
✅ Fetching data from APIs  
✅ Context API for state management  

## 🎯 Practice with Projects  
Each topic includes hands-on exercises, from simple **To-Do Lists** to advanced **Tic-Tac-Toe Multiplayer Games**.  

## 🔥 Get Started  
Check out [`learn-react.md`](./learn-react.md) and start coding!  

Happy learning! 🎉

# How to Create a React App

This guide will walk you through the steps to create a React app using 
```
create-react-app
```
, the most popular tool for bootstrapping React applications.

### **Step 1: Install Node.js and npm**
Ensure you have **Node.js** and **npm** installed. Download and install them from [nodejs.org](https://nodejs.org/).

Verify the installation:
```
node -v
```
```
npm -v
```

---

### **Step 2: Create a React App**
Use **Create React App** to set up a new React project:
```
npx create-react-app my-app
```
Replace `my-app` with your project name.

---

### **Step 3: Navigate to the Project Directory**
Move into the project folder
```
cd my-app
```

---

### **Step 4: Start the Development Server**
Run the app:
```
npm start
```
Your app will open in the browser at `http://localhost:3000`.

---

### **Step 5: Build for Production**
When ready to deploy, create a production build:
```
npm run build
```

## 📌 Introduction to React  
React is a JavaScript library for building user interfaces. It allows developers to create reusable UI components and manage state efficiently.  

📖 **Learn:**  
- [React Official Docs](https://react.dev/learn)  
- [Your First React Component](https://react.dev/learn/your-first-component)  

🎯 **Practice:**  
- Create a simple **"Hello, React!"** app.  

---

## 🏗 JSX – Writing Markup in JavaScript  
JSX allows you to write HTML-like code inside JavaScript.  

📖 **Learn:**  
- [JSX in React](https://react.dev/learn/writing-markup-with-jsx)  

🎯 **Practice:**  
- Create a **Profile Card** component using JSX.  

---

## 🔹 Components & Props  
Components are reusable UI elements. Props allow data to be passed between components.  

📖 **Learn:**  
- [Understanding Components](https://react.dev/learn/your-first-component)  
- [Props in React](https://react.dev/learn/passing-props-to-a-component)  

🎯 **Practice:**  
- Build a **User Profile Card** that takes `name` and `age` as props.  

---

## 🔄 State & Handling Events  
State helps manage data within components. Events allow interaction with UI elements.  

📖 **Learn:**  
- [React State](https://react.dev/learn/state-a-components-memory)  
- [Handling Events](https://react.dev/learn/responding-to-events)  

🎯 **Practice:**  
- Create a **Counter App** with a "Increase" and "Decrease" button.  

---

## 🎣 Hooks: `useState` & `useEffect`  
Hooks allow functional components to use state and lifecycle features.  

📖 **Learn:**  
- [useState Hook](https://react.dev/reference/react/useState)  
- [useEffect Hook](https://react.dev/reference/react/useEffect)  

🎯 **Practice:**  
- Build a **Dark Mode Toggle** app.  

---

## 📝 Handling Forms in React  
Forms allow users to input data, which can be controlled using state.  

📖 **Learn:**  
- [React Forms](https://react.dev/learn/sharing-state-between-components)  

🎯 **Practice:**  
- Build a **To-Do List** where users can add and remove tasks.  

---

## 🌍 React Router – Navigating Between Pages  
React Router helps manage navigation in single-page applications.  

📖 **Learn:**  
- [React Router Tutorial](https://reactrouter.com/en/main/start/tutorial)  

🎯 **Practice:**  
- Create a **Multi-Page Website** with Home, About, and Contact pages.  

---

## 🔗 Fetching Data from APIs (`fetch` / `axios`)  
APIs allow React apps to retrieve and display real-world data.  

📖 **Learn:**  
- [Fetching Data in React](https://react.dev/learn/you-might-not-need-an-effect)  

🎯 **Practice:**  
- Build a **Weather App** that fetches weather data from an API.  

---

## 🔄 State Management (Context API & More)  
State management helps share data across multiple components.  

📖 **Learn:**  
- [Context API](https://react.dev/reference/react/createContext)  

🎯 **Practice:**  
- Create a **Theme Switcher** that uses Context API.  

---

## 🎯 Final Practice Projects  
After learning the basics, try building these projects:  
✅ **Expense Tracker** – Add, edit, and delete expenses.  
✅ **Movie Search App** – Fetch and display movies from an API.  
✅ **Chat App (Local)** – Use `useState` to store chat messages.  
✅ **Multiplayer Tic-Tac-Toe** – Use WebSockets for real-time updates.  

---

Happy coding! 🚀
