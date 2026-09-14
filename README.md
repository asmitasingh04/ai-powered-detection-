# fake login page detection 

📌 About the Project
PhishGuard is a web-based cybersecurity awareness project designed to help users identify potentially phishing webpages through their screenshots.
Phishing websites are fake webpages that imitate trusted websites to trick users into entering sensitive information such as usernames, passwords, or other personal details.
Our system provides a simple interface where users can upload a webpage screenshot and analyze it for suspicious visual characteristics.
🎯 Problem Statement
Phishing attacks are becoming increasingly common, and fake webpages can look very similar to genuine websites. Many users may not notice small differences in the design or login interface.
This project aims to provide an easy-to-use tool that helps users become more aware of potentially suspicious webpages.
💡 Proposed Solution
The proposed system allows a user to:
Upload a screenshot of a webpage.
Preview the uploaded screenshot.
Analyze the screenshot using JavaScript-based detection logic.
Identify suspicious visual indicators.
Display a potential risk result.
Provide basic phishing-awareness information.
⚙️ How the System Works
User
  ↓
Upload Webpage Screenshot
  ↓
Image Preview
  ↓
Screenshot Analysis
  ↓
Suspicious Indicator Detection
  ↓
Risk Classification
  ↓
Display Result
✨ Key Features
📷 Webpage screenshot upload
🔍 Screenshot analysis
⚠️ Potential phishing warning
✅ Likely legitimate result
🖼️ Screenshot preview
📱 Responsive user interface
🔐 Cybersecurity awareness information
🚀 Runs directly in a web browser
🛠️ Technology Stack
Frontend
HTML5
Used to create the structure of the website and upload interface.
CSS3
Used for styling, layout, responsive design, buttons, cards, and user interface.
JavaScript
Used for image upload, preview, validation, analysis logic, and displaying results dynamically.
📂 Project Structure
phishguard/
│
├── index.html
├── style.css
├── script.js
│
├── images/
│   └── sample-screenshot.png
│
└── README.md
🔎 Detection Approach
The current prototype is a browser-based demonstration using JavaScript.
It focuses on identifying and presenting suspicious visual indicators from the uploaded screenshot.
Note: A production-level AI/ML detection system would require a trained image-classification model or an appropriate backend/API. The current version is developed as a frontend cybersecurity-awareness prototype.
🎯 Target Users
Students
Internet users
Cybersecurity beginners
Educational institutions
Users who want to learn about phishing attacks
🌐 Applications
This project can be used as an educational tool to demonstrate how phishing webpages may imitate legitimate websites.
It can also serve as a foundation for developing a more advanced phishing-detection system.
🚀 Future Scope
The project can be further enhanced with:
AI/ML-based screenshot classification
URL-based phishing detection
Browser extension
Real-time webpage analysis
Threat-intelligence integration
Deep-learning image classification
Mobile application
Combined URL + screenshot analysis
🔐 Cybersecurity Awareness
Users should not rely only on the appearance of a webpage. Before entering sensitive information, users should also verify the website address, domain name, and other security indicators.
Never enter passwords or sensitive information into a suspicious webpage.
⚠️ Disclaimer
This project is developed for educational and cybersecurity-awareness purposes.
The detection result is an automated indication and should not be considered a definitive confirmation that a webpage is safe or malicious.
📜 License
This project is intended for educational and research purposes.

