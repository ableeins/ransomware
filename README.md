██████  █████  ██████  ███  ███ ██████  ██  ██  ██████  ███████ ██████  ██   ██ ██   ██ ██   ██ ████  ████ ██   ██ ██  ██ ██    ██ ██      ██   ██  ██████  ███████ ██████  ██ ████ ██ ██████  ██  █  ██ ██  ██ █████  █████   ██      ██   ██ ██      ██  ██  ██ ██      ██ ███ ██ ██  ██ ██     ██   ██  ██  ██  ██ ██  ██      ██ ██   ███ ███   ██████  ███████ ██  ██                           

# 🕶️ Ransomware Educational Project

> ⚠️ **DISCLAIMER:** This tool is created for **educational & ethical hacking purposes** only.  
Please do not use this software to harm or compromise real systems.

---

## 👤 Author

- 🧑‍💻 GitHub: [@ableeins](https://github.com/ableeins)  
- 🔗 LinkedIn: [Ilham Husseini](https://linkedin.com/in/ilham-husseini)  
- 📸 Instagram IGN: [@ableeins](https://instagram.com/ableeins)

---

## 🚧 Project Description

This project simulates the basic behavior of a ransomware attack — **for study and awareness purposes only**. It shows how:

- 🧠 A system can be compromised
- 🔐 Files can be encrypted
- 📜 A ransom note can be generated

> ✅ This project does **not** send any data or connect to any C2 server. It's safe to test locally.

---

## 🛠️ How to Run

🖥️ **Installation:**

```bash
git clone https://github.com/ableeins/ransomware.git
cd ransomware
python3 main.py
Or run with make:

bash
Salin
Edit
make install
make run
💡 Best tested inside a virtual machine or test folder.

🔥 Features
🔒 AES encryption of target files

🧾 Auto-generated ransom note

🌀 File looping and targeting folders

🔑 Key generation (stored locally)

📂 Folder Structure
bash
Salin
Edit
ransomware/
├── main.py            # Main executable
├── encryptor.py       # Handles encryption
├── decryptor.py       # Handles decryption
├── ransom_note.txt    # Generated note
├── requirements.txt   # Python dependencies
└── README.md          # This file 😎
💣 Sample Output
pgsql
Salin
Edit
[*] Encrypting files in ./test-folder
[✔] File encrypted: photo.jpg
[✔] File encrypted: doc.txt
[!] Ransom note dropped: READ_ME_NOW.txt
🎭 Animation (CLI Tease)
Mau efek animasi typing style di CLI? Tambahkan script berikut ke main.py:

python
Salin
Edit
import time, sys
def slowprint(text):
    for char in text:
        sys.stdout.write(char)
        sys.stdout.flush()
        time.sleep(0.03)
Pakai seperti ini:

python
Salin
Edit
slowprint("Encrypting your files... 💀\n")
📄 License
yaml
Salin
Edit
MIT License – 2025 Ilham Husseini
🧠 Ethical Reminder
"If you want to defeat the darkness... you must first understand how it works."
Use this tool only for responsible learning. Never on real systems without consent.

⭐ Support
Give this repo a ⭐ if you learned something new or had fun with the simulation!
DM me on IG @ableeins kalau mau collab proyek cybersec atau tools edukasi lainnya.
