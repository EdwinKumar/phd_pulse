# PhD Pulse | Research Management & Supervisory Portal

PhD Pulse is a dual-view, interactive research tracking and supervisory portal designed for PhD candidates and academic supervisors at James Cook University (JCU).

## Key Features
- Candidate Dashboard: Literature Vault, Thesis Word Count, Dental AI Model Benchmarks, Timeline.
- Supervisor Review View: Milestone Approvals, 1-Page Meeting Digest Generator, Feedback Hub.
- Authenticity & Turnitin Scanner: Built-in similarity index pre-submission check.
- Security: Role-based authentication and PIN-based password reset system.

## Local Setup Instructions (Windows)

1. Clone or download this repository to C:\PhD_Pulse.
2. Open Command Prompt in C:\PhD_Pulse.
3. Run the following commands:

   python -m venv venv
   venv\Scriptsctivate
   pip install -r requirements.txt
   streamlit run phd_pulse_app.py

4. Access the app in your browser at http://localhost:8501.

## Default Credentials
- Candidate User: candidate | Password: phd2026 | PIN: 1234
- Supervisor User: ghazalnaz | Password: jcu2026 | PIN: 5678

## Hosting on GitHub + Streamlit Cloud
1. Upload phd_pulse_app.py, requirements.txt, and README.md to a private GitHub repository.
2. Connect your GitHub account to share.streamlit.io.
3. Deploy the repository.
