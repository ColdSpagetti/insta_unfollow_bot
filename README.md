# Instagram Unfollower Automation Bot

This is a Python-based tool that helps you unfollow people who don't follow you back on Instagram.  
It uses safe automation via `pyautogui` to open profile pages, unfollow, and even resume from where it left off!

> ⚠️ **For personal/educational use only. Use responsibly and at your own risk.**

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
- Chrome installed at:  
  `C:/Program Files/Google/Chrome/Application/chrome.exe`  
- Required Python modules:
  - `pyautogui`
  - `webbrowser`
  - `json`
  - `os`, `time`, `random`

To install pyautogui:

```bash
pip install pyautogui
```

---

## 📂 GETTING INSTAGRAM DATA

1. Go to [Instagram Data Download](https://www.instagram.com/download/request/)  
2. Request your data in **JSON format**  
3. Once your data is ready, download the ZIP file and extract:
   - `followers_1.json`  
   - `following.json`  
   from the `followers_and_following` folder  
4. Place both in the same folder as `unfollow.py`  

---

## ▶️ HOW TO USE

1. Open **Chrome** and log into Instagram manually  
2. Run the script using:

```bash
python unfollow.py
```

3. Press **Enter** when prompted  
4. The script will unfollow up to 30 people (or your custom limit)  
5. Keep **Chrome** the active window. Do not switch tabs or type while it's running.  
6. To stop the script, switch to the terminal and press `Ctrl + C`  

---

## ⚙️ CUSTOMIZATION

Edit the following inside `unfollow.py`:

- `WHITELIST` – usernames you don't want to unfollow  
- `MAX_UNFOLLOWS` – number of unfollows per session  
- `DELAY` – delay between actions for safety  

---

## 📁 INCLUDED FILES

- `unfollow.py` – the main script  
- `unfollowed_progress.json` – tracks who you’ve already unfollowed  
- `logs/` – stores logs for each run  

> ❗ **Do NOT share your personal data files (`following.json`, `followers_1.json`). Others should use their own Instagram data.**

---

## ❗ DISCLAIMER

This tool simulates human-like keyboard navigation to avoid detection.  
Avoid overuse. You are fully responsible for how your account is affected.

---

## 💡 FEEDBACK

Found a bug or have ideas to improve it?  
Open a GitHub issue or submit a pull request to contribute!
