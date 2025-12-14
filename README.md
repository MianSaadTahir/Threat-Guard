# Threat Guard

A cyber safety web app built using Python's Flask framework. It integrates real-time scanning of URLs, QR codes and files using the VirusTotal API, checks for compromised passwords via HaveIBeenPwned, blocks DDoS attempts through rate limiting, and stores users data and phishing-related data securely using SQLite databases.

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Documentation](#documentation)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
## Features
- Scan links, QR codes, and uploaded files for malware and phishing threats
- Check if emails or passwords have been exposed in data breaches using the HaveIBeenPwned API
- Secure sign-up/login system with hashed passwords
- SQLite used for storing users, phishing URLs, IPs, and breach data

## Screenshots
<img src="assets/2.png" alt="Screenshot" width="75%">
<img src="assets/3.png" alt="Screenshot" width="75%">
<img src="assets/4.png" alt="Screenshot" width="75%">
<img src="assets/6.png" alt="Screenshot" width="75%">
<img src="assets/9.png" alt="Screenshot" width="75%">

## Documentation
For a detailed overview of the project, refer to the [Documentation](./documentation) in the repository.

## Technologies Used
- Python
- Flask
- SQLite
- Jinja2
- HTML5
- CSS3
- jsQR

## Usage
1. Clone the repository:
   `git clone https://github.com/miansaadtahir/threat-guard.git`
2. Install required dependencies:
   `pip install -r requirements.txt`
3. Create a `.env` file in the root directory and add your VirusTotal API key
4. Run the application:
   `python app.py`
5. Open the local address shown in the terminal `(e.g., http://127.0.0.1:5000)` in your browser

## Contributing
Contributions, issues, and feature requests are welcome!  
Feel free to check out the [issues page](https://github.com/miansaadtahir/Threat-Guard/issues).

## License

This project is open source and available under the MIT [License](https://github.com/MianSaadTahir/Threat-Guard/blob/main/LICENSE).

