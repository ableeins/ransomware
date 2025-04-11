# 🕶️ Ransomware Educational Project

> ⚠️ **WARNING:** This repository is created for **EDUCATIONAL PURPOSES ONLY**.  
Do NOT use this tool for illegal or malicious activities. You are responsible for your own actions.  
All use cases should strictly follow ethical hacking principles and be performed in safe environments.

---

## 👤 Author Info

- 🧠 Name: **Ilham Husseini**
- 🔗 LinkedIn: [Ilham Husseini](https://www.linkedin.com/in/ilham-husseini)
- 🧑‍💻 GitHub: [@ableeins](https://github.com/ableeins)
- 🎮 IG / IGN: [@ableeins](https://instagram.com/ableeins)

---

## 🧨 Tentang Proyek Ini

Proyek ini adalah **simulasi ransomware** untuk kebutuhan:
- 💻 **Penetration Testing**
- 🧪 **Cybersecurity Research**
- 🧠 **Belajar Cara Kerja Malware Secara Etis**

Tujuan utamanya adalah memberikan wawasan tentang cara kerja ransomware, bagaimana proses enkripsi file dilakukan, dan bagaimana sistem keamanan bisa diperkuat melawan serangan semacam ini.

---

## 🛠️ Cara Menjalankan (Mode Aman)

> 🔐 Pastikan hanya dijalankan di **VM / folder testing**, **bukan di sistem utama!**

```bash
$ git clone https://github.com/ableeins/ransomware.git
$ cd ransomware
$ python3 main.py
Atau jalankan dengan virtualenv:

bash
Salin
Edit
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
$ python3 main.py
💣 Fitur
🔐 Enkripsi file lokal dengan AES

📦 Simulasi dropper

🔁 Loop untuk folder/folder dalam

🔑 Auto-generate ransom key

📄 Ransom note generator

❌ Apa yang Tidak Dilakukan Oleh Script Ini
Tidak mengirim file keluar jaringan

Tidak melakukan koneksi C2 (Command & Control)

Tidak melakukan enkripsi sistem atau boot sector

Ini adalah versi edukatif — tidak berbahaya secara nyata jika dijalankan di folder test.

📂 Struktur Direktori
bash
Salin
Edit
/ransomware
├── main.py            # Script utama ransomware simulator
├── encryptor.py       # Modul enkripsi file
├── decryptor.py       # Modul dekripsi (jika ada kunci)
├── ransom_note.txt    # Catatan tebusan yang dihasilkan
├── requirements.txt   # Dependensi
└── README.md          # Dokumentasi
🧠 Gunakan untuk:
Simulasi keamanan endpoint

Praktik membangun solusi anti-malware

Edukasi di bidang keamanan informasi

Demonstrasi bahaya serangan ransomware

🧤 Ethical Use Reminder
Jangan pernah gunakan tools seperti ini untuk mengganggu sistem orang lain.
Gunakan secara bijak, dalam jaringan tertutup atau virtual, dan hanya untuk edukasi & ethical testing.

⭐ Dukungan
Kalau kamu tertarik dengan dunia cybersecurity dan ethical hacking, jangan lupa:

⭐ Star repo ini

🧠 Fork buat kembangkan versi kamu

☕ Ngopi bareng Ilham di dunia maya (DM @ableeins 😄)

“Understand the dark to defend the light.” — Cybersecurity Wisdom
