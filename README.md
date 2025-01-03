
# MATA-SERVER

![Banner](banner.png)

![GitHub stars](https://img.shields.io/github/stars/wanzxploit/MATA-SERVER?style=social)
![Version](https://img.shields.io/badge/version-1.5-brightgreen)
![Python](https://img.shields.io/badge/python-3.7+-blue)
![PHP](https://img.shields.io/badge/php-7.4-blue)
![Platform](https://img.shields.io/badge/platform-linux%20%7C%20termux-lightgrey)

**MATA-SERVER** is the PHP web server version of the MATA project. Unlike the terminal-based PHP version hosted at [MATA Repository](https://github.com/wanzxploit/MATA), this version provides a web interface for simulating and analyzing website visits through various user agents and referrers. This project is designed for educational purposes and web traffic simulation.

---

## Features

- Web-based interface for managing simulated visits.
- Dynamic user agents and referrer injection for realistic results.
- Progress tracking and detailed logs for each visit.
- Responsive design for mobile and desktop browsers.

---

## Requirements

### Web Hosting
- PHP >= 7.4
- cURL extension enabled

### Localhost (Linux/Termux)
- PHP >= 7.4 installed
- Python >= 3.7 for running the request client
- Necessary libraries installed (`requests` for Python)

---

## Installation

### For Web Hosting
1. Download the source files from this repository.
2. Upload the files to your web hosting server.
3. Ensure that the server has PHP and the cURL extension enabled.
4. Access the application via your browser by navigating to the uploaded directory.

### For Localhost (Linux/Termux)

1. Update and install dependencies for Linux:
   ```bash
   sudo apt update && sudo apt upgrade -y
   sudo apt install git
   sudo apt install python
   sudo apt install php php-curl -y
   ```

   For Termux:
   ```bash
   pkg update && pkg upgrade -y
   pkg install git
   pkg install python
   pkg install php -y
   ```

2. Clone the repository:
   ```bash
   git clone https://github.com/wanzxploit/MATA-SERVER.git
   cd MATA-SERVER
   ```

3. Run automated server using python:
   ```bash
   pip install requests
   pip install -r requirements.txt
   python3 main.py
   ```

4. (Optional) Start the server using PHP's built-in server:
   ```bash
   php -S localhost:8080
   ```

5. Open your browser and navigate to:
   [http://localhost:8080](http://localhost:8080)


## Additional Information

### Files
- `main.py`: Run PHP to localhost instantly.
- `index.php`: Main PHP script for managing web visits.

### Support
For more details, contact [Wanz Xploit](https://github.com/wanzxploit).

---

**Disclaimer:** This tool is strictly for educational purposes and ethical use. Misuse of this tool is prohibited.
