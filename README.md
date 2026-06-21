<div align="center">
  <img src="public/icon.png" alt="Second Brain Logo" width="120" />
  <h1>Second Brain 🧠</h1>
  <p><strong>Your Invisible AI Interview Assistant</strong></p>

  [English](README.md) | [Português](README.pt.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md)
</div>

<br/>

**Second Brain** is a 100% free, invisible desktop assistant built to help professionals worldwide ace their job interviews. It runs quietly in the background, listening to the interview, and generates context-aware, first-person suggestions based on your own resume and the job description.

Powered by [Groq's](https://groq.com) lightning-fast Llama-3 inference and Whisper-large-v3, the entire process—from voice capture to intelligent suggestion—happens in milliseconds.

## ✨ Features

- **Real-Time Voice Transcription**: Uses Whisper-v3 via Groq API to transcribe the interviewer's speech with extremely high accuracy and speed.
- **Context-Aware Suggestions**: Analyzes the ongoing conversation, your provided resume, and the job description to suggest the best possible answers.
- **Multi-Language Support**: Fully localized interface and AI prompting for English, Brazilian Portuguese, European Portuguese, Spanish, French, and Italian.
- **Invisible Mode**: Built with Electron, it can be minimized to stay out of the way while you focus on the video call.
- **Privacy First**: Your resume, job description, and API keys are stored exclusively in your local machine's `localStorage`.

## 🚀 Quick Start (Download)

1. **Download the Installer:**
   Get the latest `Second Brain Setup .exe` from our [Releases](../../releases) page.
   
2. **Get a Free Groq API Key:**
   Go to [console.groq.com](https://console.groq.com/keys) and generate a free API key. This is required for the ultra-fast AI engine.

3. **Install and Configure:**
   - Open the app.
   - Paste your API Key.
   - Paste your Resume and the Job Description.
   - Select your language.
   - Click **Start Interview** and you're ready to go!

## 🛠️ Development

If you want to build from source or contribute:

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation

```bash
git clone https://github.com/2brain/second-brain.git
cd second-brain

# Install dependencies
npm install

# Start the development server
npm run dev
```

### Build for Production

```bash
# Compile and build the Electron installer
npm run dist
```
The installer will be generated inside the `dist-installers` folder.

## 🤝 Support the Project

Second Brain is open-source and free for the community. If this tool helped you land a job or nail an interview, consider buying us a coffee!

<a href="https://www.buymeacoffee.com/2brain" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 40px !important;width: 145px !important;" ></a>

## ❓ FAQ

**1. Is it really 100% free?**
Yes! The application is open-source and entirely free. You only need to create a free account on Groq to get your API key, which currently offers extremely generous free tiers.

**2. Can the recruiter see or hear the AI?**
No. Second Brain runs as an independent window on your screen. It does not inject audio into your microphone feed and does not share your screen. It is completely invisible to the interviewer.

**3. Is my data safe? Do you save my resume?**
Your privacy is our absolute priority. We do not have a database. Your API key, your resume, and the job description are saved strictly in your computer's `localStorage`. Nothing is sent to our servers (because we don't have any!).

**4. Why is the AI not answering immediately?**
The AI waits for the interviewer to finish a complete thought before generating an answer. It analyzes the context in 7-second intervals to ensure it understands the full question before giving you the script.

**5. Does it work on Mac or Linux?**
Currently, the automated releases provide a `.exe` installer for Windows. However, since it is an Electron app, you can easily clone this repository and run `npm run dist` to build it for macOS or Linux.

---

## 📝 License

Distributed under a Custom Non-Commercial License. You are free to use and study the software, but **commercial distribution or sale is strictly prohibited**. See `LICENSE` for more information.
