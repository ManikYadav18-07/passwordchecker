🚀 Overview
A lightweight Python command-line tool that evaluates password security and provides actionable feedback to help users create stronger credentials.

🔍 How It Works
The script uses the built-in re (regular expressions) module to score passwords out of 5 based on the following criteria:

Length: At least 8 characters long.

Uppercase: Contains at least one uppercase letter ([A-Z]).

Lowercase: Contains at least one lowercase letter ([a-z]).

Numbers: Includes at least one digit (\d).

Special Characters: Includes at least one symbol from [!@#$%^&*()].

Scoring System
Weak: Score of 0 to 2.

Medium: Score of 3 or 4.

Strong: Score of 5.

⚙️ How to Run
Execute the script from your terminal:

Bash
python passwordchecker.py
💡 Output
The program prompts you for a password and returns a strength rating. If the password scores under 5, it outputs a bulleted list of specific improvement suggestions. If it meets all criteria, it prints: "Your password is secure!".
