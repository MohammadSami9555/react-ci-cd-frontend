![Frontend CI Status](https://github.com/MohammadSami9555/react-ci-cd-frontend/actions/workflows/ci.yml/badge.svg)

# React CI/CD Frontend

A simple React frontend project configured with **GitHub Actions CI pipeline**.  
Every push and pull request to `main` automatically runs:

- ESLint code quality checks  
- Jest test cases  
- Production build

This project is bootstrapped using **Create React App**.

---

## 🚀 Features

- ⚛️ React (Create React App)
- 🧹 ESLint + Prettier configured
- 🧪 React Testing Library & Jest tests
- 🤖 GitHub Actions CI workflow
- 🏗 Automatic build check on every push
- 🟢 Status badge auto-updates
- 🔐 Optional branch protection support

---

## 🛠 Tech Stack

- React
- JavaScript (ES6+)
- Jest & React Testing Library
- ESLint & Prettier
- GitHub Actions

---

## 🔁 CI/CD Pipeline

The pipeline performs the following steps automatically:

1. Checkout repository
2. Setup Node environment
3. Install dependencies with `npm ci`
4. Run ESLint
5. Run unit tests
6. Build production bundle

Workflow file:  
`.github/workflows/ci.yml`

---

## 🏃‍♂️ How to Run Locally

```bash
npm install
npm start


App will run here:
👉 http://localhost:3000


🧪 Run Tests
npm test


🧹 Lint the project
npm run lint


🏗 Build for production
npm run build


Output will be generated in /build folder