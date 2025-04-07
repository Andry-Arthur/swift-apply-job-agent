# SwiftApply Executable
SwiftApply is a browser agent that applies to jobs for you.
<p align="center">
  <img src="https://github.com/user-attachments/assets/fe263478-a82e-45a5-8d40-88aa56d4aeb1" width=300/>
</p>
## 🛠️ Getting Started

### ✅ System Requirements

- Windows 10 or 11  
- Google Chrome browser  
- Internet connection  
- Google account (for JobRight.ai login)  
- Resume file (PDF or DOCX format)  

---

### 💾 Installation

1. Download the `SwiftApply.exe` file from the latest release.  
2. Place it in a folder where you have write permission.  
3. Double-click to run the application.  
> No installation or setup is required – SwiftApply runs standalone.

---

## 🚀 Using SwiftApply

### 🔹 Step 1a: Enter Your Information

Fill in the **User Information** section:

- **Email/Password** – Your Google credentials for JobRight.ai  
- **First/Last Name** – Your name as it should appear on applications  
- **Phone** – Your contact number  
- **LinkedIn URL** – Full URL to your LinkedIn profile  
- **Portfolio URL** – (Optional) Link to your website or portfolio  
- **Resume** – Click "Browse" to select your resume file.  *Note: browser agent file upload does not work properly in this release.*

---

### 🔹 Step 1b: Load from JSON (Optional)

1. Click **"Show JSON Format Example"** to see the required structure. Or see 'Sample_Info.json' in this repository.
2. Create a JSON file with your information.  
3. Use **"Browse"** to select the file.  
4. Click **"Load Fields"** to auto-fill the form.

---

### 🔹 Step 2: Select AI Model

- **Provider**: Choose between **Gemini** (recommended) or **OpenAI**  
  - Gemini models are pre-configured with a default API key  
  - OpenAI models require **your own API key**  
- **Model**: Select your preferred model  
  - Best results: `gemini-2.0-flash` or `gemini-1.5-pro`  
- **API Key**: Required for both Gemini and OpenAI (I reached the usage cap on my Gemini key)  

---

### 🔹 Step 3: Configure Chrome

- The app will try to detect Chrome from the default location  
- If installed elsewhere, click **"Browse"** and select `chrome.exe` manually  

---

### 🔹 Step 4: Add Custom Instructions (Optional)

Select your instruction mode:

- Use default instructions *(recommended for first-time users)*  
- Add instructions to default *(to refine behavior)*  
- Replace with custom instructions *(for advanced control)*  

Example custom instructions:
- `"Only apply to remote positions"`  
- `"Skip jobs requiring more than 3 years of experience"`  

---

### 🔹 Step 5: Start the Process

Click **"Start Application Process"**  
SwiftApply will:

- Launch Chrome  
- Navigate to JobRight.ai  
- Sign in with your Google account  
- Find relevant job listings  
- Complete applications automatically  
- Show real-time updates in the Status window  
- Display a completion message when finished  

---

### 🔹 Step 6: Reviewing Results

- ✅ **Success**: Popup confirms application submission  
- ⚠️ **Warning**: Incomplete application detected  
- ❌ **Error**: Message appears with error details  

---

## 💡 Tips for Best Results

- Make sure **Chrome is installed and up-to-date**  
- Use a **complete and detailed resume**  
- Ensure **OpenAI API keys** have active credits  
- Write **clear and concise custom instructions**  
- Wait patiently – the process can take several minutes per job  
- **Do not close the application** while it's running  

---

## 🧰 Troubleshooting

- **Chrome doesn’t launch**: Check Chrome path is correct  
- **Login issues**: Make sure Google credentials are valid and 2FA is off  
- **App freezes**: Click "Stop Process" and restart  
- **Error messages**: Check the Status window for info  
- **File not found**: Make sure resume path is accessible  

---

## 📣 Feedback and Support

We welcome your feedback!  
Please share your experience or report issues through our [feedback form](https://docs.google.com/forms/d/e/1FAIpQLScygOlgWMp1CmraQMn3m-xi94DwyhA77uhGuYU4IoAO5X4Okw/viewform?usp=dialog).

---

Happy Job Hunting! 🎯
