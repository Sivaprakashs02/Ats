# 📝 Ats

Ats is an ATS Resume Analyzer and Optimizer platform that helps you upload your resume, receive instant feedback, and get improvement suggestions. With a modern frontend and AI-powered backend, Ats streamlines the resume review process for job seekers looking to optimize their CVs for Applicant Tracking Systems (ATS).

---

## 🚀 Introduction

**Ats** is designed to assist job seekers in crafting resumes that pass through ATS filters and stand out to recruiters. Leveraging the power of AI (via OpenAI's Azure platform) and an intuitive web interface, Ats analyzes your resume, provides a score, and suggests actionable improvements. Whether you're submitting your resume to job portals or employer websites, Ats ensures your resume is optimized and ready.

---

## ✨ Features

- **PDF Resume Upload:** Easily upload your resume in PDF format.
- **AI-Powered Scoring:** Get instant ATS compatibility scores using Azure OpenAI.
- **Improvement Suggestions:** Receive actionable feedback to make your resume ATS-friendly.
- **Modern Web Interface:** Simple, responsive frontend for seamless user experience.
- **Secure Backend:** Robust Python backend with Flask and Gradio integrations.
- **Fast, Local Processing:** No need to share your resume with third-party services.

---

## 🛠️ Installation

### Prerequisites

- Python 3.8+
- Node.js & npm (for frontend development)
- [Azure OpenAI credentials](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/quickstart)

### Backend Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pranesh-2005/ats.git
   cd ats/backend
   ```
2. **Install Python dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Configure environment variables:**
   Create a `.env` file in `backend/` with your Azure OpenAI credentials:
   ```
   AZURE_OPENAI_KEY=your_api_key
   AZURE_OPENAI_ENDPOINT=your_endpoint_url
   AZURE_OPENAI_VERSION=your_api_version
   ```
4. **Run the backend server:**
   ```bash
   python gradioapibackend.py
   ```

### Frontend Setup

1. **Navigate to the frontend directory:**
   ```bash
   cd ../frontend
   ```
2. **Install frontend dependencies (if using build tools):**
   ```bash
   npm install
   ```
3. **Serve the frontend (simple static hosting):**
   - Open `index.html` in your browser,
   - Or use a static server like [http-server](https://www.npmjs.com/package/http-server):
     ```bash
     npx http-server .
     ```

---

## 📖 Usage

1. **Start the backend server** as described above.
2. **Open the frontend** in your browser (`index.html`).
3. **Upload your resume (PDF)** using the provided interface.
4. **View your ATS score and improvement suggestions** instantly.
5. **Iterate and improve** your resume based on the feedback!

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

> **Connect, optimize, succeed — with Ats!**


## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/Sivaprakashs02/Ats
