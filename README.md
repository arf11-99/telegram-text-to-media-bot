# 🎨 Telegram Text-to-Media Bot  
AI-powered media generator bot built with **n8n**, **Google Gemini**, and **Telegram Bot API**.

## 📌 Overview
Proyek ini adalah bot otomatis berbasis Telegram yang dapat menghasilkan **gambar dari teks** menggunakan AI generative model (Gemini 2.5 Flash Image).  
Workflow ini dibuat menggunakan **n8n** dengan integrasi switch logic untuk mendeteksi perintah tertentu dari pengguna.

Dalam versi ini, bot mampu:
- Mengambil input teks dari user
- Mengidentifikasi perintah yang mengandung kata "gambar"
- Mengirim prompt tersebut ke **Gemini Image Model**
- Menghasilkan gambar berdasarkan deskripsi teks
- Mengirimkan hasilnya kembali ke Telegram

Project ini dirancang sebagai pondasi untuk pengembangan fitur berikutnya:
- 🎬 Text-to-Video generation  
- 🖼 Advanced prompt augmentation  
- 🛠 Image variations & edits  

---

## 🧠 How It Works

```
Telegram Trigger (menerima pesan user)
        ↓
Switch (cek apakah pesan mengandung kata "gambar")
        ↓
Generate Image (Gemini 2.5 Flash Image)
        ↓
Send Photo Message (kirim hasil ke Telegram)
```

---

## 🚀 Features
✔ Text-to-Image generation (AI)  
✔ Gemini 2.5 Flash Image model integration  
✔ Telegram Bot automation  
✔ Modular workflow (mudah ditambah fitur Text-to-Video)  
✔ Clean & simple n8n workflow  

---

## 🗂 Technologies Used
- **n8n** (workflow automation)
- **Telegram Bot API**
- **Google Gemini 2.5 Flash Image**
- JSON-based workflow logic
- JavaScript Expressions inside n8n

---

## 📁 Repository Structure
```
Text-to-Media Automation.json   → Workflow utama (export dari n8n)
README.md                       → Dokumentasi project
/screenshots (opsional)         → Tambahkan screenshot bot & n8n workflow
```

---

## 💬 Example Commands
User cukup mengetik:

```
gambar kucing minum kopi di luar angkasa
```

Bot akan menghasilkan gambar sesuai prompt tersebut.

---

## 📬 Example Output (Telegram)
```
🖼️ Gambar berhasil dibuat berdasarkan deskripsi Anda!

Prompt: "kucing minum kopi di luar angkasa"
```

<img src="(tambahkan screenshot di sini)" width="350">

---

## 🛠 Setup Instructions

### 1. Import Workflow
- Buka n8n → *Import from File*
- Pilih: `Text-to-Media Automation.json`

### 2. Setup Credentials
Pastikan sudah mengatur:

- **Telegram Bot API**
- **Google Gemini API Key**

### 3. Jalankan Workflow  
Aktifkan Telegram Trigger → workflow siap digunakan.

---

## 🖼️ Recommended Screenshots
Agar repo terlihat profesional:

- Tampilan node “Generate an image”
- Hasil gambar di Telegram
- Tampilan Switch Logic
- Diagram workflow

Letakkan dalam folder `/screenshots`.

---

## 🔮 Future Enhancements
Fitur yang akan / bisa ditambahkan:

- 🎬 Text-to-Video (Gemini Image-to-Video)
- 🎨 Prompt Enhancer AI (improve prompt otomatis)
- 🖼 Variasi gambar / gaya artistik
- 🗂 Media gallery & storage
- 🤖 Auto-caption with AI
  
---

## 👤 Author  
**Arfan Fadillah**  
Programmer & Automation Enthusiast  
- Instagram: [@aefjocode](https://www.instagram.com/aefjocode)  
- YouTube: [@AefjoCode](https://www.youtube.com/@AefjoCode)

---

## ⭐ Support  
Jangan lupa beri ⭐ di repository GitHub jika proyek ini menarik bagi Anda.
