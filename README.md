SEC Filings Monitor - README

Overview

This project is a Python-based tool that monitors SEC filings (like 8-K, 10-Q, and 10-K reports) from the EDGAR database. It sends alerts when new filings are detected, helping users maintain situational awareness of critical corporate events in real-time.

Features
* Fetches the latest SEC filings from the EDGAR database.
* Filters filings by type (e.g., 8-K for material events).
* Sends email notifications when new filings are detected.
* Automates tasks using GitHub Actions or Replit Always-On services.

Prerequisites
* Python 3.x installed.
* Libraries:

Bash:
pip install requests beautifulsoup4 pandas schedule

*  Email setup: A Gmail or SMTP-compatible email account for sending notifications.
*  GitHub or Replit account (optional for deployment).

Usage
1. Clone the Repository:
  Bash: git clone https://github.com/your-username/sec-filings-monitor.git cd sec-filings-monitor

2. Set Up Email Configuration:
* Update the send_email_alert() function in script.py with your email credentials.
* Use environment variables or GitHub Secrets for storing sensitive information.

3. Run the Script Locally:
   Bash: python script.py

4. Deploy on GitHub or Replit:
* For GitHub: Use the .github/workflows/main.yml workflow to automate the script.
* For Replit: Import the repository and enable Always-On to keep the script running.

License
This project is licensed under the GNU General Public License v3.0. See the LICENSE file for more details.

Contributing
Feel free to submit pull requests or open issues for improvements and bug fixes.

Contact
For questions or feedback, contact xspwstnh@feed.readwise.io.
