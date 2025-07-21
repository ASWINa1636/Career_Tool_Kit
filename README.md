# 🎯 Career Toolkit

Career Toolkit is a terminal-based Python application designed to help students and professionals manage key career-building tasks. It includes modules for resume scanning, resume creation, SRM CGPA calculation, and action history — all powered by a MySQL backend.

## 🔧 Features

- ✅ **ATS Resume Scanner**  
  Upload your resume (PDF or DOCX) and get a realistic score based on content like skills, experience, education, and structure.

- 📝 **Resume Manager**  
  Create structured resumes via CLI and auto-generate `.docx` and `.pdf` files with hyperlinks, sections, and bullet points.

- 🎓 **SRM CGPA Calculator**  
  Calculate your CGPA across semesters and log results in the database with timestamps.

- 📜 **History Logger**  
  Automatically logs all actions (resume scans, CGPA calculations, etc.) for audit and tracking.

## 🚀 Features of each section

1. **ADS Scanner**
   - Upload a resume (PDF/DOCX)
   - Get a score based on:
     - Skills
     - Education
     - Experience
     - Contact info
     - Formatting
   - Resume scan history is saved in the MySQL database.

2. **Resume Manager**
   - Create a new professional resume.
   - Inputs include:
     - Personal details
     - Skills (hard, soft, libraries, tools)
     - Projects
     - Certifications
   - Output: A `.docx` and `.pdf` file saved in the `resumes/` folder.

3. **SRM CGPA Calculator**
   - Calculate your CGPA across semesters.
   - Stores semester GPA and final CGPA in the database for history.

4. **Overall History (Planned)**
   - Logs all user actions such as resume scans, resume creation, and CGPA calculations.
   ---

## ✨ Demo Output 
====================================
     SMART CAREER TOOLKIT
====================================
TIME: 07:53 PM
DATE: 21/07/2025
------------------------------------
1. ADS Scanner
2. Create Your Resume
3. SRM CGPA Calculator
4. History
5. Exit

Enter your choice:

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **MySQL**
- **PyMuPDF (fitz)** – PDF text extraction  
- **docx / docx2pdf** – Resume generation and export  
- **datetime, re** – Text processing and logging

-->License

MIT License
