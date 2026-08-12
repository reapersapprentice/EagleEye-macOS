<h1 align="center">Eagle Eye <sub>· for macOS</sub></h1>

<p align="center"><b>Find someone's social profiles from just a photo — on your Mac.</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-macOS-000000?logo=apple&logoColor=white" alt="macOS">
  <img src="https://img.shields.io/badge/Intel%20%26%20Apple%20Silicon-supported-success" alt="Apple Silicon & Intel">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="license">
  <img src="https://img.shields.io/badge/beginner-friendly-ff69b4" alt="beginner friendly">
</p>

---

## ✨ What is this?

Give it a name and a few photos of a person and it searches social networks, uses face recognition to confirm matches, and builds a tidy report of the profiles it believes belong to them.

This repository is a **macOS-ready conversion** — packaged so it runs on an Apple
Mac (Intel **or** Apple Silicon) without needing a Linux computer or a virtual
machine. Released by **C.Studva** under the MIT license (see `LICENSE`). Free to use, change and share.

## 🚀 Quick start

Open the **Terminal** app (press **Cmd ⌘ + Space**, type *Terminal*, hit Return),
then:

### 1. Get the files onto your Mac

```bash
git clone https://github.com/reapersapprentice/EagleEye-macOS.git
cd EagleEye-macOS
```

### 2. Install what it needs (one time)

```bash
brew install cmake cairo pango gdk-pixbuf libffi geckodriver
xcode-select --install
pip3 install -r requirements.txt
```

### 3. Run it

```bash
python3 eagle-eye.py
```

(put the target's known photos in the `known/` folder first — see that folder's note)

That's it — you're running **Eagle Eye** on your Mac. 🎉

## 🧰 What it can do

- Face-recognition matching to confirm the right person
- Searches across major social networks
- Generates a clean PDF/JSON report of the findings

## 💻 What you need

- A Mac (macOS 12 or newer) — Intel or Apple Silicon
- Python 3 (already on macOS)
- Homebrew (the Quick Start installs everything else for you)

## 🆘 New to the Terminal? Read this (30 seconds)

- The **Terminal** is just a window where you type commands. Nothing here can hurt your Mac.
- Run the commands **one line at a time**, pressing **Return** after each.
- To paste, use **Cmd ⌘ + V**.
- ⚠️ **Copy only the command itself** — never the three back-ticks around it, and
  never a line that starts with `#` (those are notes). Pasting those is the #1
  beginner mistake and causes a `parse error`.
- If a command seems stuck, it's usually just working — give it a minute.

## ⚠️ Disclaimer

**For authorized and educational use only.** Only use this against systems,
accounts or data you **own** or have **written permission** to test. You are
responsible for how you use it. See [DISCLAIMER.md](DISCLAIMER.md) for the full
terms. In short: **C.Studva, the author of this macOS conversion, is not liable**
for any damage, loss or misuse.

## 📄 License

Released by **C.Studva** under the MIT license (see `LICENSE`). Free to use, change and share.

---

<p align="center"><sub>macOS conversion crafted by <b>C.Studva</b>.</sub></p>
