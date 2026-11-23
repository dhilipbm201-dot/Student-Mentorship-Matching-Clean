MentorMatch — local CSC326 classroom prototype
Extract into a NEW folder, not your existing project.
Open the folder in VS Code. In PowerShell run:
python -m venv .venv
.venv\Scripts\python.exe -m pip install -r requirements.txt
.venv\Scripts\python.exe app.py
Enter a faculty demo admin password (16+ characters) when prompted.
Open http://127.0.0.1:5000
Admin email: admin@mentorship.local
Register fictional student and mentor accounts. Admin verifies mentor. Student finds mentor and requests mentorship; mentor accepts. Dashboard conversation link supports saved coursework messages, visible to faculty. Refresh to retrieve new messages. Meetings supports video requests; admin approves or rejects. Faculty arranges actual supervised conferencing separately; no live call is built in. No CSS or JavaScript files; HTML browser defaults are intentional. SQLite database is created automatically, messages survive restarts. Admin password is set at startup. Local only, not production-ready; no public deployment. Do not use real student data. Keep the database private.
