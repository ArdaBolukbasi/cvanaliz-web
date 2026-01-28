<div align="center">
  <img src="static/favicon.png" alt="Logo" width="100" height="auto" />
  <h1>🚀 CV Analysis & Matching System</h1>
  <p>
    <strong>Next-Gen AI Powered Resume Evaluator</strong>
  </p>
  
  <p>
    <a href="#features">Features</a> •
    <a href="#technologies">Technologies</a> •
    <a href="#installation">Installation</a> •
    <a href="#usage">Usage</a>
  </p>

  ![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Flask](https://img.shields.io/badge/Flask-2.0+-000000?style=for-the-badge&logo=flask&logoColor=white)
  ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-AI-4285F4?style=for-the-badge&logo=google&logoColor=white)
</div>

<br />

## 🌟 Overview

Refine your career path with **CV Analysis & Matching**, a state-of-the-art tool capable of dissecting, scoring, and optimizing resumes against real-world job descriptions. 

Built with **Google's Gemma 3 (12B IT)** model, this application goes beyond simple keyword matching. It understands context, evaluates design, checks for ATS compatibility, and provides actionable feedback—all wrapped in a stunning, modern interface.

---

## 🎨 Interface Preview

<div align="center">
  <img src="static/screenshot.png" alt="Application Screenshot" style="border-radius: 20px; box-shadow: 0 20px 60px rgba(0,0,0,0.3);" width="800" />
</div>

> *Experience a sleek, glassmorphism-inspired UI designed for clarity and engagement.*

---

## ✨ Key Features

- **🧠 Advanced AI Analysis**: Utilizes **Google Gemini (Gemma-3-12b-it)** to deeply understand resume content.
- **📊 Comprehensive Scoring**: Evaluates CVs based on a strict rubric:
  - 🎨 Design & ATS Compatibility (Max 15 pts)
  - 🛠️ Technical Skills (Max 30 pts)
  - 🚀 Projects & Experience (Max 35 pts)
  - 🎓 Education (Max 20 pts)
- **🎯 Job Description Matching**: Paste a job ad to see exactly how well the applicant fits the role.
- **🔍 Specialized Reports**:
  - ✅ **Strong Points**: What makes the candidate shine.
  - ⚠️ **Improvement Areas**: Critical feedback for growth.
  - 🤖 **ATS Check**: Ensure robots can read the CV.
  - 🔑 **Missing Keywords**: Sektör standard terms the CV lacks.
  - 🗣️ **Interview Prep**: Custom generated technical questions.
- **💬 Interactive AI Chat**: Ask specific questions about career advice or CV details directly to the AI.
- **📱 Responsive Design**: Perfectly usable on desktop, tablet, and mobile devices.

---

## 🛠️ Technologies Used

We chose a robust and modern stack to ensure performance, scalability, and developer experience.

| Technology | Why We Used It |
|------------|----------------|
| **Python 3** | The powerhouse of AI and backend development. Simple, readable, and vast ecosystem. |
| **Flask** | A lightweight WSGI web framework. It provides the flexibility we need without the bloat, perfect for rapid prototyping and microservices. |
| **Google Gemini API** | Powered by the **Gemma-3-12b-it** model. It offers superior reasoning capabilities for text analysis compared to traditional NLP methods. |
| **HTML5 & CSS3** | **Vanilla CSS** was used to craft a custom, high-performance design system without the overhead of heavy frameworks. |
| **Markdown** | Used for rendering the rich-text responses from the AI into beautiful, readable HTML reports. |
| **Glassmorphism UI** | A visual style that uses transparency and background blur to create a sense of depth and modernity. |

---

## 🚀 Installation & Setup

Follow these steps to get the project running on your local machine.

### Prerequisites
- Python 3.9 or higher
- A Google Cloud API Key for Gemini

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/cv-analysis-app.git
   cd cv-analysis-app
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   # Windows
   .\venv\Scripts\activate
   # macOS/Linux
   source venv/bin/activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Environment Variables**
   Create a `.env` file in the root directory and add your API key:
   ```env
   GENAI_API_KEY=your_google_ai_api_key_here
   ```

5. **Run the Application**
   ```bash
   python app.py
   ```

6. **Visit the App**
   Open your browser and navigate to `http://localhost:5000`.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

<br />

<div align="center">
  <sub>Built with ❤️ by using <strong>Python</strong> and <strong>Google AI</strong></sub>
</div>
