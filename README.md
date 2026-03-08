# Spec2Code Copilot

AI-powered learning platform that transforms natural language project ideas into structured, professional software specifications.

## 🎯 Purpose

Spec2Code Copilot bridges the gap between ideation and professional software development by helping students and early-stage developers create industry-standard documentation.

## 🚀 Quick Start

### Prerequisites
- Python 3.11 or higher
- pip package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd spec2code-copilot
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run app.py
```

4. Open your browser to `http://localhost:8501`

## 📖 How to Use

1. Enter your project idea in the text area
2. Provide as much detail as possible about features, users, and goals
3. Click "Generate Specification"
4. Review the generated sections:
   - Project Summary
   - Functional Requirements
   - Suggested Architecture
   - Development Plan
5. Download the specification as Markdown

## 🏗️ Project Structure

```
spec2code-copilot/
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
├── requirements.md     # Project requirements document
├── design.md          # System design document
├── README.md          # This file
└── .kiro/
    └── steering/      # AI assistant guidance files
```

## 🎓 Hackathon Context

- **Event:** AI for Bharat Hackathon (AWS)
- **Track:** AI for Learning & Developer Productivity
- **Team:** KiroCrafters

## 🎯 Target Users

- Computer science students learning software engineering
- Self-taught developers transitioning to professional development
- Hackathon participants needing quick project structuring
- Bootcamp graduates preparing for industry work

## 🔮 Future Enhancements

- Real AI integration (AWS Bedrock/OpenAI)
- User authentication and project saving
- Iterative refinement of generated specs
- Multiple export formats (PDF, HTML)
- GitHub integration for direct repository creation

## 📝 License

MIT License - See LICENSE file for details

## 👥 Team

KiroCrafters - AI for Bharat Hackathon 2024
