# TextSimplify-AI

A web application that uses an AI-powered summarisation API to extract and condense articles from any URL — paste a link, get the key points instantly.

🔗 **Live Demo:** [textify-ai.netlify.app](https://textify-ai.netlify.app)

---

## What it does

TextSimplify-AI lets you paste any article URL and returns a clean, concise summary of the content. Instead of reading through long articles, you get the essential information in seconds. It is useful for quickly scanning news, research, or blog content without opening multiple tabs.

---

## Built with

| Technology | Purpose |
|---|---|
| React + Vite | Frontend framework and build tool |
| Redux Toolkit | Global state management |
| Tailwind CSS | Utility-first styling |
| RapidAPI (Article Extractor & Summarizer) | AI summarisation engine |
| Netlify | Deployment and hosting |

---

## Features

- Paste any article URL and receive an AI-generated summary
- History of previously summarised articles stored in session
- Copy summary to clipboard with a single click
- Clean, responsive UI built with Tailwind CSS
- Fast development and build times via Vite

---

## Getting started

### Prerequisites

- Node.js v16 or higher
- A RapidAPI account and API key for the [Article Extractor and Summarizer API](https://rapidapi.com/restyler/api/article-extractor-and-summarizer)

### Installation

```bash
# Clone the repository
git clone https://github.com/dennisnyarko/TextSimplify-AI.git

# Navigate into the project directory
cd TextSimplify-AI

# Install dependencies
npm install
```

### Environment setup

Create a `.env` file in the root of the project and add your RapidAPI key:

```
VITE_RAPID_API_ARTICLE_KEY=your_api_key_here
```

### Running locally

```bash
npm run dev
```

The app will be available at `http://localhost:5173`

### Building for production

```bash
npm run build
```

---

## Project structure

```
TextSimplify-AI/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── services/        # Redux RTK Query API config
│   └── App.jsx
├── index.html
├── tailwind.config.js
├── vite.config.js
└── package.json
```

---

## Screenshots


<img width="3024" height="1728" alt="image" src="https://github.com/user-attachments/assets/da5d54a9-543e-4ada-9f07-d77802ecf83c" />

<img width="1546" height="922" alt="image" src="https://github.com/user-attachments/assets/9948d284-096d-4a11-a802-61bad342c868" />



---
