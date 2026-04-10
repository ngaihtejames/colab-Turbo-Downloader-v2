# 🚀 Colab Turbo Downloader

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ngaihtejames/colab-Turbo-Downloader-v2/blob/main/downloader.ipynb)

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Type-No--Code%20Tool-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
</p>

---

A **high-performance, beginner-friendly file downloader** built for **Google Colab** with seamless **Google Drive integration**.

> ⚡ Fill the inputs → click **Runtime → Run all** → your file downloads automatically.

---

## ✨ Features

- 🧠 **No code required** — simple UI inputs
- ☁️ **Google Drive integration**
- 🚀 **Multi-threaded downloads**
- 🔁 **Retry support for unstable connections**
- 💾 **Memory-efficient streaming**
- 🔄 **Automatic fallback mode**
- 📊 **Live progress bar**

---

## 📁 Repository Structure

```
.
├── downloader.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## ⚡ Quick Start

1. Click **Open in Colab**
2. Enter:
   - Download URL
   - File name (optional)
   - Threads (optional)
3. Click **Runtime → Run all**
4. Approve Drive access
5. Wait for:
   ```
   ✅ Done
   ```

---

## ⚠️ Notes

- Some servers may not support multi-threading
- Private/login links may fail
- Large downloads depend on Colab session stability

---

## 💡 Tips

- Keep default settings if unsure
- Check Google Drive for output file
- Ensure enough storage space

---

## 📦 Requirements

```
requests>=2.31.0
tqdm>=4.66.0
```

---

## 📜 License

This project is licensed under the MIT License — see the LICENSE file for details.
