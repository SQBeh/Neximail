# 📧 Neximail - Temporary Email Automation

## Overview
Neximail is a command-line tool that automates the creation, management, and monitoring of temporary email addresses using the TempMail API. It allows users to generate disposable email addresses, check their inbox, and interact with emails without needing a personal email account.

This tool is useful for:
- Preventing spam on your primary email.
- Testing email-based services.
- Protecting privacy while signing up for online services.
- Save you old indox mail+address. 

## Features
✔ Generate a random temporary email address.  
✔ Create a custom/login email address with a chosen domain.  
✔ Check inbox and read received emails.  
✔ Save email history locally for easy retrieval.  
✔ View email details, including sender, subject, and body.  
✔ Download and view email attachments.  
✔ Simple and interactive command-line interface.  

## Installation

### Prerequisites
- Python 3.x installed on your system.
- Required dependencies: `requests`, `json`, `os`, `random`, `shutil`.
- Internet connection (required for API access).

### Setup Termux 
1. **Clone the repository**
   ```sh
   git clone https://github.com/SQBeh/Neximail.git
   cd Neximail
   ```
2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the script**
   ```sh
   python nmail.py
   ```
3. **Run with short commands**
   ```sh
   cd Neximail && python nmail.py
   ```

## Usage

### 1. Generating a Temporary Email
Run the script and select the option to create a new temporary email. You can choose:
- A **randomly generated** email address.
- A **custom email** with a preferred domain.

### 2. Checking Your Inbox
- The script automatically fetches new emails.
- Displays sender, subject, and email body.
- Supports attachments with preview and download options.

### 3. Email History & Saved Addresses
- Previously used email addresses are stored in a local database.
- Users can log in to old temporary email accounts.

### 4. Exiting the Script
- Use `Ctrl + C` to stop execution.
- Select the exit option in the main menu.

## API Integration
This script interacts with:
- [TempMail API](https://temp-mail.io/) for email generation and inbox management.

## File Structure
```
📂 yourrepo
 ├── mmail.py             # Main script
 ├── requirements.txt     # Python dependencies
 ├── Database/
 │   ├── all_domain.json  # Stores email history
 │   ├── domain.txt       # Stores current session email
 │   ├── mailchk.mao      # Temporary email cache
 │   ├── maocount.mao     # Inbox count tracking
 ├── README.md            # Project documentation
```

## Screenshots
*(Add relevant screenshots of terminal interface, email generation, and inbox checking.)*

## Issues & Support
If you encounter any issues, feel free to open an issue on the [GitHub repository](https://github.com/yourusername/yourrepo/issues).

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact & Socials
- **GitHub:** [SQBeh](https://github.com/SQBeh)  
- **YouTube:** [SQBEHPS](https://youtube.com/@SQBEHPS)
- **YouTube:** [SQBVerse](https://youtube.com/@SQBVerse)  
- **Facebook:** [SQB EHPS Service](https://www.facebook.com/profile.php?id=61554399397116)  
