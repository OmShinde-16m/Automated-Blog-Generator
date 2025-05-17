# 📝 Automated Blog Generator

Automated Blog Generator is a web application that generates well-structured, AI-written blog posts based on user input prompts. The application uses a large language model to create high-quality content with formal structure, headings, and coherent paragraphs.

This README will guide you through the setup process, usage, and key features of the project.

---

## 📑 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Troubleshooting](#troubleshooting)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)

---

## 📘 Project Overview

The **Automated Blog Generator** simplifies the content creation process by transforming a simple topic or prompt into a fully written blog post using an AI language model. It offers a responsive web interface and provides real-time blog generation with an elegant UI and optional dark mode.

The result is a professional, structured blog post ready to be published or refined further.

---

## ✨ Features

- **Prompt Input:** Users enter a blog topic or prompt in a text area.
- **AI-Powered Generation:**
  - Uses a language model to generate high-quality blogs.
  - Formal tone, structured paragraphs, and headings.
- **Interactive UI:**
  - Light/Dark theme toggle.
  - Real-time blog content display.
- **Error Handling:**
  - Displays descriptive messages for API or backend failures.

---

## 🧰 Technologies Used

### Frontend

- **HTML5:** Structure of the webpage
- **CSS3:** Styling and responsive layout
- **JavaScript:** Interactivity and theme toggling

### Backend

- **FastAPI:** Web framework for Python
- **Groq API Client:** For generating blogs using a language model (e.g., LLaMA 3.3 70B)
- **Jinja2:** Templating engine for rendering HTML
- **Dotenv:** For managing environment variables

---

## ⚙️ Setup Instructions

### 1. Prerequisites

- Python 3.9 or later
- Pip (Python package manager)

### 2. Clone the Repository

```bash
git clone https://github.com/your-username/automated-blog-generator.git
cd automated-blog-generator
