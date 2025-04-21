# Automated-CV-Scoring-AI-Agent
# https://colab.research.google.com/drive/1QBkPtnAXFNsvoa8CT47X7_56Xv0Z3CZJ#scrollTo=WceyBG7VP0Zi

This project is an automated CV scoring and feedback generation system that evaluates resumes based on a provided job description. The system uses AI models to calculate how well a resume matches the job description and provides personalized feedback to candidates via email.

## Features

- **Job Description Matching**: The system matches the resume to a given job description (e.g., for an AI Engineer) using cosine similarity.
- **Resume Parsing**: It supports both PDF and DOCX file formats for resume uploads.
- **Personalized Feedback**: The AI generates a positive, encouraging feedback email for the candidate based on their resume.
- **Email Feedback**: The system extracts the candidate's email from the resume and sends them the feedback.
  
## Requirements

- Python 3.x
- Google Colab (optional, for easy deployment)
- The following Python packages are required:
  - `gradio`
  - `requests`
  - `PyPDF2`
  - `python-docx`
  - `scikit-learn`
  
# You can install the dependencies using the following command:
pip install gradio requests PyPDF2 python-docx scikit-learn
Email Feedback Format
The feedback email will include the following:

Resume match score

Job description match percentage

A personalized message detailing strengths and possible improvements based on the candidate's experience.

# Limitations
Currently, the system only supports PDF and DOCX files.

The email is extracted based on a regex pattern, so it may not work if the email is not in a standard format.

# Contributions
Feel free to contribute to this project! If you'd like to help improve the code, report bugs, or suggest new features, please fork the repository and create a pull request.
