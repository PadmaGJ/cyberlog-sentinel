# CyberLog Sentinel 🛡️

**Live Demo:** [https://your-username.github.io/cyberlog-sentinel/](https://your-username.github.io/cyberlog-sentinel/) *(Replace with your actual GitHub Pages link after deploying)*

CyberLog Sentinel is an intelligent log analysis tool designed for cybersecurity professionals and enthusiasts. It leverages the power of Google's Gemini API to provide rapid, AI-driven insights into log files, helping to identify potential threats and suggest immediate incident response actions.

![CyberLog Sentinel In Action](https://storage.googleapis.com/gemini-prod-us-west1-assets/cyberlog_demo.gif)

---

## ✨ Features

* **Bring Your Own API Key**: Securely operates in any environment by using the visitor's own Gemini API key, which is never stored or shared.
* **AI-Powered Analysis**: Utilizes the Gemini API to perform a deep analysis of log contents, distinguishing between routine events and potential security threats.
* **Prioritized Threat Highlighting**: Automatically flags events requiring immediate attention, such as potential malware, phishing attempts, or brute-force attacks.
* **Actionable Response Suggestions**: Generates a concise list of initial incident response steps based on the identified high-priority threats.
* **Modern, Responsive UI**: A sleek, dark-themed interface built with Tailwind CSS, ensuring a great experience on any device.
* **Drag & Drop File Upload**: Easily upload `.log` and `.txt` files.

---

## 🚀 Tech Stack

* **Frontend**: HTML5, CSS3, JavaScript (ES6+)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/)
* **AI & Machine Learning**: [Google Gemini API](https://ai.google.dev/)
* **Icons**: [Font Awesome](https://fontawesome.com/)

---

## 🛠️ How to Use the Live Demo

To see the magic happen on the live demo, you will need a Google Gemini API key.

1.  **Get a Free API Key**:
    * Visit [Google AI Studio](https://ai.google.dev/).
    * Click "**Get API key**" and create a new key. The free tier is generous and more than enough for this demo.
2.  **Paste the Key**:
    * Copy your newly generated API key.
    * Paste it into the "Your Gemini API Key" input field at the top of the CyberLog Sentinel app.
3.  **Upload & Analyze**:
    * Upload a `.log` or `.txt` file. Sample log files are not provided, but you can easily find examples online or use your own.
    * Click "Analyze File" and see the AI-powered results!

---

## 🔧 Local Development Setup

This project is a single-file, client-side application and does not require a complex setup.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/cyberlog-sentinel.git](https://github.com/your-username/cyberlog-sentinel.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd cyberlog-sentinel
    ```
3.  **Open `index.html` in your browser:**
    * You can open the `index.html` file directly in a web browser.
    * For the best experience, it's recommended to serve the file with a simple local server. If you have Python installed:
        ```bash
        # For Python 3
        python -m http.server
        ```
        Then, navigate to `http://localhost:8000` in your browser.

---

*This project was developed as a proof-of-concept to showcase the integration of Large Language Models (LLMs) like Google's Gemini into practical cybersecurity tooling.*
