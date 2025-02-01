# SKIP: Terms of Service Summarization Tool

## Overview
SKIP is a browser extension that simplifies terms of service and privacy policies into easy-to-understand summaries. It also provides comparative analysis, educational content, and personalized risk assessment.

## Features
- **Multi-Language Support:** Summarize terms of service in multiple languages.
- **Comparative Analysis:** Compare terms of service across multiple services.
- **Educational Content:** Learn about common legal terms with tooltips.
- **Personalized Risk Assessment:** Tailor summaries based on your priorities.

---

### Installation

### Prerequisites
Before you begin, ensure you have the following installed:
- **Python 3.8 or higher**
- **Google Chrome** (or another Chromium-based browser)

## Step 1: Clone the Repository
1. Open your terminal or command prompt.
2. Run the following command to clone the repository:
   ```bash
   git clone https://github.com/defidan1/SKIP.git
3. Navigate to the project folder:
```bash
 cd SKIP
```
 Step 2: Install Dependencies
1. Install the required Python libraries by running:
   ```bash
   pip install flask googletrans==4.0.0-rc1 langdetect transformers torch
   
## Step 3: Run the Backend
1. Start the Flask backend server:
   ```bash
   python app.py
2. The backend will run at http://localhost:5000.

## Step 4: Load the Browser Extension
1. Open Google Chrome and go to chrome://extensions/.
2. Enable **Developer mode** (toggle in the top-right corner).
3. Click **Load unpacked** and select the **SKIP** folder.

### Usage

## Summarize a Page
1. Click the **SKIP** icon in your browser.
2. Select a language and click **Summarize This Page**.
3. The summary will appear in the popup.

## Compare Documents
1. Paste two terms of service documents into the text areas.
2. Click **Compare** to see the results.

## Set Preferences
1. Go to the **Preferences** section to customize your risk assessment.

## Feedback
We'd love to hear your feedback! Click the **Feedback** button in the extension to share your thoughts.

### Contributing
If you'd like to contibute to SKIP, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
4. Push to the branch:
   ```bash
   git push origin feature-name
5. Open a pull request on GitHub.

### License
This project is licensed under the MIT License.
See the **LICENSE** file for details.
