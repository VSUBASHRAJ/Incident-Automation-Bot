# AI-Powered Ticket Resolution Automation Project Video Links 
---






## Project Demonstration
Video Walkthrough:
[Watch Project Demo](https://drive.google.com/file/d/1UGLSGXuNzYLO9aP_6xecp-ODTHCe2qnK/view?usp=drive_link)
[Watch Project Demo](https://drive.google.com/file/d/14CaEVtQWvrF09p2yYMWco44Ti4uhn0ty/view?usp=drive_link)




  

---

## Overview
This project is an end-to-end Robotic Process Automation (RPA) solution built using Automation Anywhere to automate IT support ticket handling.  

The bot extracts ticket data (Task ID, Email, Issue) from Excel, interacts with a web-based ticket system, retrieves relevant solutions, and sends responses via email.

---

## Key Features
- Extracts ticket data from Excel (Task ID, Email, Issue)
- Automates web interaction (login, form filling, navigation)
- Identifies relevant solutions based on issue type
- Sends automated email responses with solutions
- Handles high-volume repetitive tickets efficiently
- End-to-end workflow automation with minimal manual intervention

---

## Tech Stack
- Automation Anywhere A360
- Excel Automation
- Web Automation
- Email Automation (SMTP/Outlook)
- Conditional logic and loops

---

## How It Works
1. The bot reads ticket data from an Excel file  
2. Opens the ticket web application  
3. Inputs Task ID and Email  
4. Navigates to the issue resolution section  
5. Retrieves the appropriate solution  
6. Sends an email containing:
   - Ticket ID  
   - Issue  
   - Solution  
7. Logs the execution status  

---

## Impact
- Reduced manual effort by 60%  
- Improved response time by 50%  
- Automated handling of 50+ tickets per day  
- Ensured consistent and accurate responses  

---

## Project Structure
/project  
│── bot_files/  
│── excel_data/  
│── web_app/  
│── email_module/  
│── logs/  
│── README.md  

---

## Setup Instructions
1. Install Automation Anywhere A360  
2. Import the bot into Control Room  
3. Configure:
   - Excel file path  
   - Web application URL  
   - Email credentials  
4. Run the bot  

---

## Prerequisites
- Automation Anywhere access  
- Excel file with ticket data  
- Web-based ticket system  
- Configured email service  

---

## Sample Input (Excel)

| Task ID | Email           | Issue            |
|--------|-----------------|------------------|
| 101    | user@mail.com   | Password Reset   |
| 102    | user2@mail.com  | App Not Opening  |

---

## Future Enhancements
- AI-based issue classification using NLP  
- Dashboard for ticket analytics  
- Real-time notifications  
- Cloud integration  

---

## Author
Subash Raj V  
GitHub: https://github.com/VSUBASHRAJ
