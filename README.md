# Resume Screening App
Resume Screening App With Python and Machine Learning

This application predicts the job category of a resume using Natural Language Processing (NLP) and a Support Vector Classifier (SVC).

## Features
- Upload resumes in PDF, DOCX, or TXT format.
- Automatically extracts text from the uploaded resume.
- Predicts the job category using a pre-trained machine learning model.
- Built with Streamlit for a simple, interactive user interface.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yash2083/ResumeScreening.git
   cd ResumeScreening
   ```

2. Install the required dependencies:
   ```bash
   pip install -r reqiurements.txt
   pip install streamlit scikit-learn python-docx PyPDF2
   ```

## Usage

1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Open your browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`).
3. Upload a resume file and view the predicted category.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
