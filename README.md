# ApexBlock Privacy Filter

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/ApexBlock-Privacy-Filter-Browser-List/ci.yml?branch=main&style=for-the-badge)](https://github.com/chirag127/ApexBlock-Privacy-Filter-Browser-List/actions/workflows/ci.yml)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg?style=for-the-badge)](https://creativecommons.org/licenses/by-nc/4.0/)
[![TypeScript](https://img.shields.io/badge/TypeScript-6.x-blue.svg?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-7.x-purple.svg?style=for-the-badge&logo=vite)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-4.x-blue.svg?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)

An intelligent, client-side privacy filter powered by a multi-provider AI fallback chain. This project is built on a cutting-edge, frontend-only architecture, ensuring maximum user privacy and control.

## 🚀 Architecture: Frontend-Only (December 2025 Standard)

This project operates entirely within your browser. There is **no backend server**, **no database**, and **no Node.js runtime**. This serverless approach guarantees that your data and API keys never leave your machine.

-   **Direct API Calls:** All interactions with AI providers (Cerebras, Gemini, Groq, etc.) are made directly from the browser using the `fetch` API.
-   **User-Provided API Keys:** You provide your own API keys, which are stored securely in your browser's `LocalStorage`. They are never transmitted to any server.
-   **Client-Side Logic:** All processing and AI orchestration happens on the client-side.

## ✨ Features

-   **Multi-Provider AI Fallback:** Intelligently switches between AI providers (Cerebras, Gemini, Groq, Mistral, NVIDIA, Cloudflare) to ensure reliability.
-   **Exponential Backoff:** Implements a robust retry mechanism for API calls.
-   **Modern Tech Stack:** Built with Vite 7, TypeScript 6, Tailwind CSS 4, and Biome for a fast, reliable, and maintainable codebase.
-   **Secure & Private:** Your data and keys are yours and yours alone.

## 🛠️ Quickstart

To get started with ApexBlock locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/chirag127/ApexBlock-Privacy-Filter-Browser-List.git
    cd ApexBlock-Privacy-Filter-Browser-List
    ```

2.  **Install dependencies:**
    This project uses `pnpm` as the package manager.
    ```bash
    pnpm install
    ```

3.  **Set up environment variables:**
    There are no backend environment variables. All API keys are managed in the UI.

4.  **Run the development server:**
    ```bash
    pnpm dev
    ```
    The application will be available at `http://localhost:5173`.

## 💻 Tech Stack

-   **Framework:** Vite 7
-   **Language:** TypeScript 6.x
-   **Styling:** Tailwind CSS v4
-   **State Management:** Signals
-   **Linting/Formatting:** Biome
-   **CI/CD:** GitHub Actions

## 🤝 Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for details on our code of conduct and the process for submitting pull requests.

## 📄 License

This project is licensed under the [CC BY-NC 4.0 License](LICENSE).
