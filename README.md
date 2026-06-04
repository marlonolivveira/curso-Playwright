# 🧪 Jornada Milhas — E2E Test Automation with Playwright

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)](https://playwright.dev/)
[![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)](https://angular.io/)

End-to-End test automation suite for **Jornada Milhas**, a fictional travel booking startup, built with **Playwright** and **Angular**. Tests cover the full user journey including registration, login, flight search and profile editing.

---

## 📖 About the Project

Jornada Milhas is a fictional StartUP where users can search for flights and filter results by price, connections, and airlines. This project focuses on implementing **E2E automated tests** to ensure the reliability and quality of the system's core features.

**Tested features:**
- User registration and login
- Profile editing
- Flight search with filters (price, connections, airlines)

---

## 🛠️ Technologies

| Tool | Purpose |
|------|---------|
| [Playwright](https://playwright.dev/) | E2E test framework |
| [Angular 16](https://angular.io/) | Front-end framework (application) |
| [TypeScript](https://www.typescriptlang.org/) | Programming language |
| [Node.js](https://nodejs.org/) | Runtime environment |

---

## ⚙️ Project Structure

```
curso-Playwright/
├── src/
│   ├── app/
│   │   ├── autenticacao/     # Login & registration modules
│   │   ├── busca/            # Flight search module
│   │   ├── core/             # Core services
│   │   ├── home/             # Home page
│   │   └── shared/           # Shared components
│   ├── assets/
│   └── environments/
├── angular.json
├── package.json
└── tsconfig.json
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- [Angular CLI](https://angular.io/cli)

### Install dependencies

```bash
npm install
```

### Run the application

```bash
ng serve
# Then open http://localhost:4200/
```

> ⚠️ You also need to run the backend server used in the course.

### Run Playwright tests

```bash
npx playwright test
```

### Run tests with UI mode

```bash
npx playwright test --ui
```

---

## ✍️ Author

**Marlon Oliveira** — QA Engineer  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/marlon-oliveira-qa)
