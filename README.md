
<p align="center">
  <img src="https://i.postimg.cc/Sx9vnKfs/file-bat.png" width="400"/>
</p>

<h1 align="center"> FILE BAT </h1>

<p align="center">
  🚀 Powered by <b> BANGLADESH CYBER SQUAD</b><br>
  📆 Year: 2025
</p>

---

## 🦇 FILE BAT

A fast, clean and powerful archive password‑cracking tool for **ZIP, RAR, 7Z** and more — built for Termux and Linux.

FILE BAT focuses on speed, stability and a smooth, hacker‑style terminal experience.

---

## ✅ Highlights

* 🚀 **High‑speed brute‑force** (multi‑threaded)
* 📚 **Wordlist attack** support
* 🎛️ Live attempt dashboard (Rich UI)
* ⚡ Instant status update when password is found
* 📦 Auto extraction after successful crack
* 🎨 Clean colors and readable output
* 📱 Termux‑friendly, lightweight
* 🔧 Works with **ZIP, RAR, 7Z** (and P7ZIP)

---

## 📥 Installation

### Termux

```bash
pkg update -y && pkg upgrade -y
pkg install python -y
pkg install unrar -y
pkg install p7zip -y
pip install rich rarfile
```

### Linux (Ubuntu/Debian)

```bash
sudo apt update
sudo apt install python3 python3-pip unrar p7zip-full
pip3 install rich rarfile
```

---

## ▶️ How to Run

```bash
python file-bat.py
```

Follow the on‑screen steps:

1. Select target file
2. Select extraction folder
3. Choose **Brute‑Force** or **Dictionary** mode
4. Set worker threads
5. Watch live cracking attempts in a clean UI

---

## 🧠 Attack Modes

### 🔹 Brute‑Force

* Choose preset charsets
* Set start and max length
* Multi‑threaded cracking

### 🔹 Dictionary

* Use your own wordlist
* Best when the password is common or predictable

---

## 📂 Supported Formats

* `.zip`
* `.rar`
* `.7z`
* `.7zip`

FILE BAT auto‑detects archive type and uses the best method.


---

## ⚠️ Disclaimer

FILE BAT is for **educational use** and **authorized security testing only**.
Never use it on files you do not own or have permission to access.

---

## 👤 Developer

**BLACK ZER0**
---

