## 📌 InternGrow Tasks

- **Task 1 — Resume Screening System:** [Live Demo](https://alina911-hub.github.io/InternGrow-Frontend-Track/resume-screener.html)
- **Task 2 — AI Customer Support Chatbot:** [Live Demo](https://alina911-hub.github.io/InternGrow-Frontend-Track/task-2-chatbot/)
- **Task 3 — Vision Bench (AI Image Classification):** [Live Demo](https://alina911-hub.github.io/InternGrow-Frontend-Track/task-3-vision-bench/)

# InternGrow — Intelligent Resume Screening System

An AI-powered resume screening tool that automatically analyzes resumes, matches them against a job description, and ranks candidates — all running client-side in the browser, no backend required.

## 🚀 Live Demo
👉 **[Try it live](https://alina911-hub.github.io/InternGrow-Frontend-Track/resume-screener.html)**

## ✨ Features

- **Resume Upload** — supports PDF and DOCX, drag-and-drop, multiple files at once
- **Text Extraction** — `pdf.js` for PDFs, `mammoth.js` for DOCX
- **OCR Fallback** — scanned/image-based PDFs are automatically processed with `Tesseract.js` on-device
- **Skill Identification** — NLP-lite keyword and phrase matching against a 120+ skill bank (programming languages, frameworks, tools, soft skills)
- **Job Matching** — paste any job description; the system extracts required skills and compares them against each resume
- **Resume Scoring** — weighted score combining JD match percentage and overall skill density
- **Candidate Ranking** — automatically sorts and ranks all uploaded resumes
- **AI Score Dashboard** — visual bar chart, summary stats, and ranked table
- **Export Results** — download screening results as CSV or JSON

## 🛠️ Tech Stack

| Purpose | Library |
|---|---|
| PDF text extraction | pdf.js |
| DOCX text extraction | mammoth.js |
| OCR (scanned PDFs) | Tesseract.js |
| Charts / Dashboard | Chart.js |
| Skill matching | Custom NLP-lite keyword engine |

## 📖 How to Use

1. Download `resume-screener.html` (or clone this repo)
2. Open the file in any modern browser (Chrome/Edge recommended)
3. Paste a job description in the left panel
4. Upload one or more resumes (PDF/DOCX)
5. Click **Run Screening**
6. Review matched skills, scores, and rankings
7. Export results as CSV or JSON if needed

No installation, no server, no API keys — everything runs locally in your browser.

## 📂 Project Structure

```
resume-screener.html   # Full application (HTML + CSS + JS in one file)
README.md              # Project documentation
```

## 🔮 Possible Upgrades

- Backend integration (Python/Flask) for persistent storage of candidates
- Advanced NLP using spaCy or transformer-based models for smarter skill extraction
- Resume-to-JD semantic similarity using embeddings instead of keyword matching
- User authentication and saved screening history

## 👩‍💻 Author

Built by Alina as part of the InternGrow internship program (Week 1 task — Intelligent Resume Screening System).
