#  Part of Udemy Course: React y TypeScript - La Guía Completa Creando +10 Proyectos
This project is part of the Udemy course "React y TypeScript - La Guía Completa Creando +10 Proyectos" by Juan Pablo De la Torre Valdez. The course teaches React and TypeScript by building real-world applications such as shopping carts, budget apps, patient managers, and full-stack projects. The Budgeting App (Project 06) focuses on using Context API for state management, expense categorization, date filtering, and visualizing expenses with charts.

For more information about the course: Udemy Course Link.

# Budgeting App
This repository is part of a series of personal projects aimed at improving my development skills and building a portfolio of diverse applications.

# Project Overview
The Budgeting App is built using modern web technologies such as React, TypeScript, and TailwindCSS. It allows users to manage their expenses, track income, and visualize their budget through a clean and user-friendly interface.

# Technologies Used
React: JavaScript library for building the user interface.
TypeScript: Enhances JavaScript with static typing for better maintainability.
Vite: Fast development server and build tool for modern web projects.
TailwindCSS: Utility-first CSS framework for rapid UI development.
ESLint: Linting tool for maintaining code quality and consistent style.
Netlify: Hosting platform used for deploying the application live.
Purpose
This project is part of a portfolio series designed as a self-training exercise to strengthen my proficiency in different technologies and frameworks. Each project in the series focuses on building various types of applications, from budgeting tools to other personal finance, productivity, and educational applications.

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
