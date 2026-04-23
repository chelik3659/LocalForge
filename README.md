# ⚙️ LocalForge

**LocalForge** is a privacy‑first, offline AI coding assistant that runs entirely on your machine.  
It understands your project structure, helps with code generation, refactoring, and answers questions — **without sending any data to the cloud**.

> 🔒 100% offline · 🧠 Local LLMs · 📁 Project‑aware · ⌨️ Instant help

---

## ✨ Features

- 🚫 **Fully offline** – No API keys, no subscriptions, no data leaks
- 🧠 **Local AI models** – Uses Ollama (DeepSeek Coder, CodeLlama, Qwen, etc.)
- 📂 **Project‑aware** – Sees your whole codebase, answers in context
- ⚡ **Instant global hotkey** – `Ctrl+J+K` to get AI help from any editor
- 💾 **Chat history** – Saved locally, never leaves your machine
- 🌙 **Dark theme** by default
- 💰 **Free forever** – donations welcome, but never required

---

## 📥 Installation

### 1. Install Ollama

Download and install [Ollama](https://ollama.com) for your OS.

### 2. Pull a code model

Open a terminal and run:

```bash
ollama pull deepseek-coder
```

Other recommended models: `codellama`, `qwen2.5-coder`, `llama3.2`.

### 3. Install LocalForge

Grab the latest release for your platform:

- **Windows**: `LocalForge-win.exe`
- **Linux**: `LocalForge.AppImage`

Make the AppImage executable:

```bash
chmod +x LocalForge.AppImage
```

---

## 🚀 How to use

1. **Launch LocalForge** – open the application.
2. **Select your project folder** – the AI will index its structure.
3. **Start chatting** – ask anything about your code.
4. **Use the global hotkey** – highlight code in any editor, press `Ctrl+J+K`, and ask for help instantly.

All processing is done locally on your machine.

---

## 🛡️ Privacy & License

- **No telemetry, no tracking, no cloud.**  
  Your code never leaves your computer.

- **Donation link is protected.**  
  This project is source‑available, but any modification or redistribution **must keep the original donation link**.

See [`LICENSE.txt`](LICENSE.txt) for full terms.

If you find LocalForge useful, consider supporting the developer:  

👉 **[Donate via CloudTips](https://pay.cloudtips.ru/p/c9294618)**

---

## 🧠 Built with

- [Electron](https://www.electronjs.org/)
- [Ollama](https://ollama.com)
- JavaScript / Node.js

---

## 📬 Contact & contributions

This is a solo project. For bugs or suggestions, open an issue on GitHub.  
Pull requests are welcome, but any modifications must keep the donation link intact.

---

*Forge your code, locally.*  
**LocalForge – you control the forge.**
