# Instagram Unfollower Automation Bot

This is a Python-based tool that helps you unfollow people who don't follow you back on Instagram.
It uses safe automation via `pyautogui` to open profile pages, click unfollow, and even resumes from where it left off!

> ⚠️ For personal and educational use only. Use responsibly and at your own risk.

---

## 🔧 FEATURES

- Automatically unfollows non-followers based on your Instagram data
- Skips whitelisted accounts (like your crush or bestie 😉)
- Keeps track of unfollowed users so you can resume later
- Delays between actions to mimic human behavior
- No image recognition required — just keyboard navigation

---

## 🧰 REQUIREMENTS

- Windows 10 or 11 (tested)
- Python 3.9 or higher
- Chrome installed at: `C:/Program Files/Google/Chrome/Application/chrome.exe`
- Required Python modules:
  - `pyautogui`
  - `webbrowser`
  - `json`
  - `os`, `time`, `random`

Install dependencies:
```bash
pip install pyautogui
