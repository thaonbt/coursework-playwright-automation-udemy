# 🎓 Coursework: Playwright Automation Testing (JS/TS)
> **Subtitle:** Web & API Automation Testing from Scratch, AI Agents, & Frameworks

This repository contains all the hands-on exercises, automation scripts, and end-to-end testing frameworks I built while completing the comprehensive Playwright course by **Rahul Shetty** on Udemy.

---

### 🛠️ Tech Stack & Advanced Features
*   **Automation Tool:** Playwright (Latest Version)
*   **Languages:** TypeScript / JavaScript
*   **Testing Types:** Web UI Testing & API Automation Testing
*   **BDD Framework:** Cucumber Integration
*   **Advanced Topics:** AI Testing Agents & CI/CD Pipeline Integrations

### 🚀 Local Setup & Installation Guide

Follow these step-by-step instructions to initialize the project and install all required Playwright library dependencies locally:

#### 1. Prerequisites
*   Download and install **Node.js** (LTS version recommended) on your machine.

#### 2. Project Initialization & Setup
Create a new directory and initialize Playwright inside it:
```bash
# Create a new project folder
mkdir PlaywrightAutomation

# Navigate into the created folder
cd PlaywrightAutomation

# Scaffold a new Playwright project with configuration files
npm init playwright@latest
```
*(The command above automatically configures your `package.json`, generates scaffolding files, downloads required browser binaries, and installs all system dependencies inside a newly created `node_modules` folder).*

---

### 🧪 Executing & Debugging Tests

Once initialization is complete, navigate into your project directory and use the following core CLI commands to run, debug, or generate tests:

#### 💻 Running Tests via Command Line
```bash
# Run all end-to-end tests in headless mode (default)
npx playwright test

# Run tests in headed mode to see the live browser window execution
npx playwright test --headed

# Run tests strictly on the Desktop Chrome environment
npx playwright test --project=chromium

# Run tests targeting a specific file path
npx playwright test tests/example.spec.js
```

#### 🛠️ Advanced Testing & Debugging Modes
```bash
# Start the interactive Playwright UI Mode for live time-travel debugging
npx playwright test --ui

# Launch Playwright Inspector to step through test code line-by-line
npx playwright test --debug

# Launch the interactive Test Generator to auto-generate tests using Codegen
npx playwright codegen
```

#### 📊 Viewing HTML Test Reports
```bash
# Open the dashboard of your last executed test run results
npx playwright show-report
```

---

### 📂 Key Project Files to Check Out
Feel free to open and review these generated files to understand how the test suite is structured:
*   `./tests/example.spec.js` – Example starter end-to-end test script.
*   `./tests-examples/demo-todo-app.spec.js` – Demo Todo application reference test cases.
*   `./playwright.config.js` – Central configuration file for target browsers, timeouts, and reporters.

---

### 📜 Verified Certificate
*   _Status:_ Course currently in progress. The official completion certificate will be linked here upon graduation.

---
_Disclaimer: This repository is maintained strictly for personal learning, code practice, and future reference. For more detailed training materials, visit the official [Playwright Documentation](https://playwright.dev/docs/intro)._
