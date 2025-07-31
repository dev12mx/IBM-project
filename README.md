# AI Resume & Cover Letter Generator
An intelligent and easy-to-use web app built with Streamlit that allows users to generate a professionally formatted résumé and customized cover letter in seconds. Designed to streamline your job application process with smart form inputs and beautiful template rendering using Jinja2.
# What Makes This App Stand Out
🚀 Features
	•	Instant Resume & Cover Letter Generation
Fill out your details once and generate both documents instantly.
	•	Clean, Dual-Tab UI
Navigate easily between “Generate Résumé” and “Generate Cover Letter” tabs in a distraction-free layout.
	•	Template-Driven Output
Uses Jinja2 templates to render outputs with clean formatting and spacing.
	•	Streamlit-Powered Interface
Lightweight frontend using Streamlit for rapid deployment and intuitive design.
	•	Exportable Output
Easily copy and paste the generated text or plug it into PDF/Word templates
# Project Structure
ResumeApp/
├── app.py                 # Streamlit app with form logic and tabbed interface
├── resume_template.txt    # Jinja2 template for résumé output
├── cover_template.txt     # Jinja2 template for cover letter output
├── screenshots/           # UI screenshots for README documentation
├── requirements.txt       # List of required Python packages
└── README.md              # This file
# Getting Started
1. Clone the repository
2. git clone-https://github.com/dev12mx/IBM-project
3. ⁠(Optional) Create a virtual environment

python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

3. Install the required packages
pip install -r requirements.txt

4. Run the application
streamlit run app.py

# How It Works
•	User fills out details like name, email, phone, professional title, skills, experience, etc.
	•	Based on the selected tab, either a résumé or a cover letter is generated.
	•	The form data is rendered using Jinja2 templates with conditional logic and formatting.
	•	The generated output appears directly within the Streamlit app.

# Requirements
Python 3.x
	•	Streamlit
	•	Jinja2
	•	datetime 

# Demo
Résumé Generator UI:

<img width="1570" height="917" alt="Screenshot 2025-07-30 062128" src="https://github.com/user-attachments/assets/87459ba4-eb26-41d4-97fb-19030b99df06" />
<img width="980" height="553" alt="Screenshot 2025-07-30 062151" src="https://github.com/user-attachments/assets/8029d06f-96c0-4792-a252-c049662717b8" />

Cover Letter Generator UI:

<img width="1570" height="917" alt="Screenshot 2025-07-30 062216" src="https://github.com/user-attachments/assets/4c14facb-716e-41b7-8974-fbbd8148dbd6" />
<img width="916" height="457" alt="Screenshot 2025-07-30 062234" src="https://github.com/user-attachments/assets/8ad5957f-4cf2-4687-a689-887659c43b6a" />

#  Developed By
Made with ❤️ by Devansh Srivastava
B.Tech CSE | Passionate about automation, clean UI, and making job applications smarter



