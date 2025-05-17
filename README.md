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


### 3. Install Dependencies

```bash
pip install fastapi uvicorn python-dotenv groq jinja2
Make sure to create a .env file in the project root with your Groq API key:

ini
Copy
Edit
GROQ_API_KEY=your_api_key_here
4. Run the Application
bash
Copy
Edit
uvicorn main:app --reload
The backend will run on http://127.0.0.1:8000.

🧪 Usage
Open your browser and go to: http://127.0.0.1:8000

Enter your blog topic or idea into the input field.

Click "Generate Blog".

The AI-generated blog content will appear below the form.

Use the moon/sun icon in the header to toggle between light and dark modes.

🔗 API Endpoints
Endpoint	Method	Description
/	GET	Loads the homepage with prompt form
/	POST	Accepts blog prompt and returns generated blog

🛠️ Troubleshooting
Common Issues
API Key Error:

Ensure GROQ_API_KEY is defined in the .env file.

Template Not Found:

Ensure the index.html and error.html are placed in the app/templates/ folder.

Static Files Not Loading:

CSS should be in app/static/style.css.

🚀 Future Improvements
Add multilingual blog generation support.

Allow users to download blog as a .docx or .pdf.

Integrate with a CMS (e.g., WordPress) for instant publishing.

Add blog outline previews before generation.

🤝 Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.

Create a feature branch:

bash
Copy
Edit
git checkout -b feature/your-feature
Commit your changes:

bash
Copy
Edit
git commit -m "Add feature"
Push to the branch:

bash
Copy
Edit
git push origin feature/your-feature
Open a Pull Request.
