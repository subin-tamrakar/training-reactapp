# DevOps React App

This is a modern web application built with [React](https://react.dev/) and [Vite](https://vitejs.dev/). It serves as a foundational project for demonstrating DevOps practices, including Continuous Integration and Continuous Deployment (CI/CD) pipelines.

## Application Overview

The application is a lightweight React starter project that features:
- **Fast Development Server**: Powered by Vite for instant Hot Module Replacement (HMR).
- **Interactive UI**: A simple counter component to demonstrate state management.
- **Modern Tooling**: configured with ESLint for code quality and Vitest for testing.

## Install nodejs using nvm on the the server
[nvm](https://github.com/nvm-sh/nvm)

## Jenkins CI/CD Pipeline assignments
Create a `Jenkinsfile` that defines the CI/CD pipeline. The pipeline automates the software delivery process through the following stages:

1.  **Install Dependencies**: Installs project dependencies using `npm ci` to ensure a clean and reproducible environment.
2.  **Build**: Compiles the React application for production using `npm run build`.
3.  **Lint**: Analyzes the code for potential errors and styling issues using ESLint (`npm run lint`).
4.  **Test**: Executes the test suite using Vitest (`npm test`) to verify application logic.
5.  **Deploy**: Simulates a deployment by creating a `deploy` directory and copying the build artifacts (`dist/*`) into it.

## Getting Started Locally

1.  **Install Dependencies**:
    ```bash
    npm install
    ```

2.  **Run Development Server**:
    ```bash
    npm run dev
    ```

3.  **Run Tests**:
    ```bash
    npm test
    ```

4.  **Build for Production**:
    ```bash
    npm run build
    ```