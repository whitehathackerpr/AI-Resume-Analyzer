# AI Resume Analyzer 🚀

<div align="center">

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/flask-2.0.0-green.svg)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

</div>

## 📝 Overview

AI Resume Analyzer is a powerful web application that helps job seekers optimize their resumes for specific job descriptions. Using advanced NLP techniques and machine learning, it provides detailed analysis, suggestions, and enhancements to make your resume stand out to both ATS systems and hiring managers.

## ✨ Features

- **Smart Resume Analysis**: Analyzes your resume against job descriptions using NLP
- **ATS Optimization**: Identifies and fixes ATS compatibility issues
- **Grammar Checking**: Detects and suggests improvements for grammatical errors
- **Keyword Analysis**: Shows matching and missing keywords from job descriptions
- **Resume Enhancement**: Provides actionable suggestions to improve your resume
- **Customizable Design**: Choose from various templates and design options
- **PDF Export**: Download your enhanced resume in a professional PDF format
- **Real-time Preview**: See changes instantly before downloading

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **NLP**: spaCy, scikit-learn
- **PDF Processing**: PyPDF2, python-docx
- **Grammar Checking**: language-tool-python
- **PDF Generation**: reportlab

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/whitehathackerpr/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer
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

4. Download the spaCy language model:
```bash
python -m spacy download en_core_web_sm
```

5. Create the uploads directory:
```bash
mkdir uploads
```

### Running the Application

1. Start the Flask server:
```bash
python app.py
```

2. Open your browser and navigate to:
```
http://127.0.0.1:5000
```

## 📋 Usage Guide

1. **Upload Your Resume**
   - Click the upload area or drag and drop your resume (PDF or DOCX)
   - Maximum file size: 16MB

2. **Enter Job Description**
   - Paste the job description in the text area
   - The more detailed the description, the better the analysis

3. **Customize Options**
   - Choose your preferred writing style
   - Select keyword density
   - Enable/disable ATS optimization
   - Customize design options

4. **Analyze Resume**
   - Click "Analyze Resume" to start the analysis
   - View detailed results and suggestions

5. **Download Enhanced Resume**
   - Preview the enhanced resume
   - Download as PDF with your preferred design

## 📊 Analysis Results

The application provides:

- **Match Percentage**: How well your resume matches the job description
- **Keywords Found**: Important keywords present in your resume
- **Missing Keywords**: Keywords from the job description not in your resume
- **ATS Compatibility**: Issues that might affect ATS parsing
- **Grammar Suggestions**: Improvements for better readability
- **General Suggestions**: Actionable tips to enhance your resume

## 🎨 Design Customization

Customize your resume with:

- **Colors**: Choose primary and secondary colors
- **Font Size**: Adjust text size (10-14pt)
- **Line Spacing**: Modify spacing between lines
- **Skills Chart**: Include/exclude skills visualization
- **Template Style**: Modern, Professional, Creative, or Minimal

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [spaCy](https://spacy.io/) for NLP capabilities
- [Flask](https://flask.palletsprojects.com/) for the web framework
- [Bootstrap](https://getbootstrap.com/) for the UI components
- [ReportLab](https://www.reportlab.com/) for PDF generation

## 📞 Support

For support, please:
- Open an issue in the GitHub repository
- Email: [your-email@example.com](mailto:your-email@example.com)
- Join our [Discord community](https://discord.gg/your-server)

## 📈 Future Enhancements

- [ ] Multi-language support
- [ ] Cover letter generator
- [ ] LinkedIn profile analyzer
- [ ] Interview preparation tips
- [ ] Resume version control
- [ ] Integration with job boards

---

<div align="center">
Made with ❤️ by [Your Name](https://github.com/your-username)
</div> 