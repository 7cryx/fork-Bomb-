# Fork Bomb Prank (Educational Purpose Only)

## ⚠️ Warning
This script is intended **only for educational purposes** and **harmless pranks**. Do **not** use it for malicious activities, as it can overload a system if misused. Run it in a **safe environment** like a virtual machine.

---

## 📌 What is a Fork Bomb?
A **fork bomb** is a script that continuously creates new processes, consuming system resources until the system crashes or becomes unresponsive. This batch script does exactly that but should only be used for learning and fun **(with permission).**

---

## 📝 How It Works
- The script opens **multiple instances of itself** in a loop.
- Over time, this **exhausts system resources**, causing the computer to slow down or freeze.
- Restarting the system is required to stop it.

---

## 🚀 Usage (Prank Version)
1. Save the following code as `hello.bat`:
   ```batch
   @echo off
   title HELLO
   echo "Prank Activated!"
   timeout /t 1 /nobreak >nul
   start hello.bat
   goto hello
   ```
2. **DO NOT** run it on an important system.
3. Run it in a **safe, controlled environment** (like a virtual machine).

---

## 🛑 How to Stop It?
If accidentally executed:
1. **Press `Ctrl + Shift + Esc`** to open Task Manager.
2. **Find multiple `cmd.exe` processes**.
3. **End them manually** or force restart the system.

---

## ❗ Disclaimer
This script is for **educational purposes only**. The author is **not responsible** for any misuse or system damage. Use it **responsibly** and **with permission**. Prank safely! 😃

