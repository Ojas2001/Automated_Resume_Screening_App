# Automated_Resume_Screening_App

## Project Description

This application automates resume screening by comparing resumes with job descriptions using **Mistral AI's LLM model**. It generates a detailed report assessing candidate suitability and provides results in both UI and downloadable PDF formats. Ideal for recruiters and hiring managers to streamline candidate evaluation.

## Key Features

✨ **Dual Input Support**  
  - Upload **resumes** (PDF/DOCX) and **job descriptions** (PDF/DOCX)
  
🤖 **AI Analysis**  
  - Mistral AI LLM performs semantic comparison of the resume and the JD
  
📊 **Comprehensive Report**  
  - Detailed suitability assessment with strengths/gaps
  - Evaluation result is - Best Fit/Good Fit/Moderate Fit/Poor Fit/ Bad Fit 
  - Key matching criteria highlighted

📥 **Dual Output**  
  - Instant UI results with visual indicators
  - Professional PDF report generation

## Tech Stack

- **Mistral AI** (LLM analysis)
- **Python** (backend logic)
- **Streamlit** (web interface)
- **PyMuPDF**/**python-docx** (text extraction)
- **ReportLab** (PDF generation)

## Installation

1. **Clone repository**
2. **Install dependencies**
3. **Set up Mistral AI**
- Get API key from [Mistral AI platform](https://mistral.ai/)
- Create `.env` file:
  ```
  MISTRAL_API_KEY=your_api_key_here
  ```

## Usage

1. **Start application**

2. **Upload files**  
<img src="https://via.placeholder.com/600x200?text=Upload+Interfac" width="400">

- Resume (PDF/DOCX)
- Job Description (PDF/DOCX)

3. **View AI Analysis**  
<img src="https://via.placeholder.com/600x400?text=Results+Dashboard" width="400">

- Suitability percentage
- Key match/mismatch points
- Skill gap analysis

4. **Download PDF Report**  
<img src="https://via.placeholder.com/600x200?text=PDF+Report+Preview" width="400">

- Professional format
- Contains full analysis
- Export/share capability
