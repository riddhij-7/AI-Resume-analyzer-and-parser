# AI Resume analyzer and parser 
Our AI Resume Parser & Analyzer is an intelligent system designed to streamline the recruitment process by automatically extracting, analyzing, and evaluating candidate resumes. Built using advanced Natural Language Processing (NLP) and Machine Learning techniques, this tool converts unstructured resume files into structured data, making it easier for recruiters and hiring platforms to assess candidate profiles efficiently.

📁 Repository Structure

APP.py: Main application script that handles resume parsing and job recommendation logic.

RESUME.html: Frontend HTML file for uploading resumes and displaying results.

Resume job recommendation system.ipynb: Jupyter Notebook demonstrating the job recommendation process.

extractedinfo and hiring process.ipynb: Notebook detailing the extraction of information and the hiring process logic.

UpdatedResumeDataSet.csv.zip: Dataset containing manually labeled resume data for training and testing.

Sample Resumes:
 Example resumes in PDF and TXT formats (e.g., Teacher.pdf, designer.pdf, advocate.txt, etc.).​
## 📂 Project Structure

```text
├── app.py                          # Main backend logic for parsing and recommendation
├── RESUME.html                     # Frontend interface for uploading and viewing
├── Resume job recommendation system.ipynb
├── extractedinfo and hiring process.ipynb
├── UpdatedResumeDataSet.csv.zip   # Training & testing dataset
├── /Sample Resumes/               # Sample resumes (PDF/TXT)
```
🔍 Key Features

Resume Parsing: Extracts essential information such as name, contact details, education, work experience, and skills from uploaded resumes.

Job Recommendation: Suggests suitable job roles based on the extracted information using predefined mappings and logic.

Manual Data Annotation: The dataset used for job prediction was manually labeled to ensure accuracy in recommendations.

Frontend Interface: A simple HTML interface (RESUME.html) allows users to upload resumes and view the parsed information and job suggestions.​

🔧 Setup & Installation
  ```bash 
  git clone https://github.com/your-username/ai-resume-parser.git
  cd ai-resume-parser
  pip install -r requirements.txt
  python app.py
```
📄 Sample Output

Upon uploading a resume, the system will display extracted information such as:
Name: John Doe
Email: john.doe@example.com
Skills: Python, Data Analysis, Machine Learning
Recommended Job Role: Data Scientist​

📌 Notes
✅ Python 3.9+ recommended
🌐 Internet connection required (for web-based interactions)
🕵️‍♀️ Refresh page or restart server after changes for updates to reflect

✨ Acknowledgements
This project was built as part of a resume screening system to support automated recruitment.
Special thanks to the open-source ML and NLP communities 💙

📫 Contact
Connect with me on https://www.linkedin.com/in/riddhi-jathar-b2434a288/

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-Web_App-lightgrey?style=for-the-badge&logo=flask)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://opensource.org/licenses/MIT)
