# 🛡️ VulnScan Lite
VulnScan Lite is a lightweight cybersecurity web application developed using Python and Flask.
The project performs basic vulnerability assessment by analyzing HTTP security headers and SSL configuration of a given website.

This project is designed for educational and internship purposes and works on both Linux and Windows systems.

## 🎯 Project Objective
Example for VulnScan Lite:
• 	Analyze website security headers
• 	Detect missing HTTP security headers
• 	Validate SSL/TLS configuration
• 	Classify website security risk levels (🟢 LOW / 🟠 MEDIUM / 🔴 HIGH)
• 	Provide basic security recommendations
## 🚀 Key Features
### HTTP Security Header Analysis
- Analyzes website response headers for security best practices
- 	Detects missing or misconfigured headers such as CSP, X-Frame-Options, and X-Content-Type-Options
### 	SSL/TLS Validation
- 	Validates SSL/TLS certificates to check if they are properly configured
- 	Flags invalid or insecure SSL setups
### 	Cookie Security Check
- 	Identifies cookies with Secure and HttpOnly flags
- 	Highlights potential risks in cookie handling
### 	CMS Detection
- 	Recognizes popular content management systems like WordPress, Joomla, Drupal, or marks as Unknown
### Risk Scoring System
- 	Classifies website security risk leve
-	🟢 LOW
- 🟠 MEDIUM
- 🔴 HIGH
### 	Basic Security Recommendations
- 	Provides actionable suggestions to improve website security based on findings
### 	Backend Logic & Frontend UI
- 	Robust backend scanning logic with a simple, user-friendly web interface
### 	Cross-Platform Support
  - 	Works seamlessly on both Linux and Windows systems
### 	Disclaimer Section
- 	Clearly states the project is for educational and internship purposes only
### 🚀 Key Features
- Simple and user-friendly web interface
- Passive security scanning (no attacks)
- Risk scoring system with visual indicators
- Security recommendations based on findings
- Cross-platform support (Linux & Windows)

## 🛠️ Tools & Technologies Used
- Python 3
- Flask (Web Framework)
- Requests Library
- SSL & Socket Modules
- HTML & CSS
- Operating Systems: Linux / Windows
### 📂 Project Structure
VulnScan-Lite/ ├── app.py ├── requirements.txt ├── templates/ │ └── index.html ├── static/ │ └── style.css

### ▶️ How to Use the Project

### 1️⃣ Download the Project
Open this GitHub repository
Click Code → Download ZIP
Extract the ZIP file

### 2️⃣ Install Python
Ensure Python 3.8 or above is installed: python --version

### 3️⃣ Create Virtual Environment (Recommended)
🔹 Linux / macOS python3 -m venv venv source venv/bin/activate

🔹 Windows python -m venv venv venv\Scripts\activate

### 4️⃣ Install Required Dependencies
pip install -r requirements.txt

### 5️⃣ Run the Application
python app.py

You will see:

Running on http://127.0.0.1:5000

### 6️⃣ Automatic Browser Launch
Once you run the application using:

python app.py
The web application will automatically open in your default web browser.

If it does not open automatically (rare case), you can manually open:

http://127.0.0.1:5000
