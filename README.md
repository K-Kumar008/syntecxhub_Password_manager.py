# syntecxhub_Password_manager.py
This project is a local password manager developed using Python 3 on Kali Linux.  It allows users to securely store, retrieve, delete, and search credentials while ensuring that  all sensitive information is encrypted before being saved to disk. 
# 🔐 Secure Password Manager (Python)

A simple **command-line password manager** written in Python that securely stores credentials using **strong encryption**.  
All passwords are encrypted using a master password and stored locally in an encrypted vault.

---

## ✨ Features

- 🔑 Master password protection
- 🔐 AES encryption via Fernet
- 🧂 PBKDF2 key derivation with salt
- ➕ Add new credentials
- 🔍 Retrieve stored credentials
- ❌ Delete entries
- 🔎 Search stored websites/apps
- 📋 View all saved entries in a table
- 📁 Encrypted local storage (no cloud)

---

## 🛠️ Technologies Used

- Python 3
- `cryptography` library
- PBKDF2-HMAC-SHA256
- Fernet symmetric encryption

---

## 📦 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/password-manager.git
cd password-manager
