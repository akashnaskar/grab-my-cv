# 🌟 Grab My CV

## Problem Statement
Today, companies receive thousands of resumes for a single job opening. Most of these applications are either:
- **Not optimized for Applicant Tracking Systems (ATS)**
- **Fail to highlight the most relevant skills**
- **Are poorly structured and grammatically weak**

As a result, great candidates are often **filtered out automatically**, costing businesses valuable talent and wasting recruitment resources.

---

## Business Impact
- **Reduced Hiring Costs:** Automatically pre-screen resumes before manual review.
- **Improved Candidate Quality:** Identify and prioritize high-potential candidates.
- **Enhanced Employer Branding:** By providing detailed feedback reports, even rejected candidates feel valued.
- **Scalable AI Recruitment:** Ready for integration into any company's hiring portal as an AI Resume Advisor.

---

## Project Achievement
I built a **full-stack AI-powered resume analyzer** that:
- Extracts personal information intelligently
- Analyzes grammar, structure, and content quality
- Matches resumes against job descriptions
- Estimates salaries based on role, experience, and location
- Visualizes ATS scores and generates **professional PDF reports**
- Offers an **AI career coach** chat feature powered by OpenAI GPT-3.5

> **Goal achieved:** Built a scalable, modular, and recruiter-grade resume analysis engine entirely with Python, OpenAI APIs, and Streamlit.

---

## How It Works (In-Depth)

### 1. Application Flow
- **Frontend:** Built with **Streamlit**, providing a smooth UI for uploading resumes and job descriptions.
- **Backend Services:**
  - **Text Extraction:** From PDFs, Word documents, and plain text.
  - **Personal Info Detection:** Uses regex and AI for accurate extraction.
  - **ATS Compliance Analysis:** Scores resume readiness against real-world hiring systems.
  - **Grammar + Language Analysis:** Deep text critique across grammar, spelling, punctuation, and style.
  - **Job Matching:** Matches resumes to specific job descriptions, recommending missing skills.
  - **Salary Estimation:** Predicts salary ranges based on role, location, and experience.
  - **PDF Reporting:** Generates elegant, detailed analysis reports.

### 2. Core Files
| File | Purpose |
|:---|:---|
| `requirements.txt` | Manages all library dependencies |
| `test_imports.py` | Quickly checks if critical packages are installed correctly |
| `devcontainer.json` | Sets up a portable, reproducible dev environment using VSCode + Docker |
| `app.py` | Main application logic; ties frontend UI and backend AI services together |

---

## Future Improvements
- **Productionize the Architecture:**
  - Split into `services/`, `api/`, `components/`, and `utils/` for even cleaner codebase
- **Database Integration:**
  - Store analyzed resumes and user sessions securely
- **User Accounts:**
  - Allow users to track and improve multiple resumes
- **Fine-tuned LLMs:**
  - Train custom OpenAI models for industry-specific resume analysis
- **Multi-language Support:**
  - Analyze resumes in non-English languages (using SpaCy + multilingual transformers)

---
Perfect!  
Here’s a **super clean, professional \"How to Run\" section** you can directly **copy-paste** into your `README.md`.

---

## How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
```

### 2. Setup a virtual environment
```bash
python -m venv venv
```
Activate it:
- Windows:
  ```bash
  venv\\Scripts\\activate
  ```
- macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure OpenAI API Key
Create a `.streamlit/secrets.toml` file:
```toml
OPENAI_API_KEY = "your-openai-api-key-here"
```

Or alternatively, load it via a `.env` file.

### 5. Launch the application
```bash
streamlit run app.py
```
The app will be available at:  
`http://localhost:8501/`

---

## Alternative Setup: Using DevContainers

If you have Docker and VSCode:
- Open the project in VSCode
- Choose \"Reopen in Container\"
- The environment will be automatically configured.

---

✅ This guide ensures your project is fully operational locally in minutes.

---

# 📋 Quick Tip
If you face port issues:
```bash
streamlit run app.py --server.port 8502
```
to manually set another port.

---

## Final Note
> This project demonstrates my ability to design, build, and deliver **real-world AI applications** that directly address modern recruitment challenges.
>
> **It stands out** because it not only analyzes resumes but transforms them into **powerful career tools** for candidates and companies alike.

---

### 🚀 Tech Stack
**Python 3.11** | **Streamlit** | **OpenAI GPT-3.5** | **SpaCy** | **NLTK** | **PyPDF2** | **Docker/DevContainers** | **VSCode**

---

Made with ❤️ by Akash Naskar
