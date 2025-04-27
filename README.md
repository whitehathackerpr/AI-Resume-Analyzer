# AI Resume Analyzer

An AI-powered tool that helps job seekers optimize their resumes for specific job roles by analyzing content, providing suggestions, and calculating match percentages with job descriptions.

## Features

- Upload resumes in PDF or DOCX format
- Keyword analysis and extraction
- Content suggestions for improvement
- Match percentage calculation
- Clean, intuitive user interface
- Detailed feedback and recommendations

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-resume-analyzer.git
cd ai-resume-analyzer
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Download SpaCy language model:
```bash
python -m spacy download en_core_web_sm
```

5. Run the application:
```bash
python app.py
```

## Usage

1. Access the web interface at `http://localhost:5000`
2. Upload your resume (PDF or DOCX format)
3. Enter the job description
4. Click "Analyze" to get detailed feedback and suggestions

## Technologies Used

- Backend: Flask (Python)
- NLP: SpaCy
- Frontend: Bootstrap
- File Processing: PyPDF2, python-docx
- Machine Learning: scikit-learn

## License

MIT License 