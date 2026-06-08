# 🔐 Password Manager

A Password Manager application built using Python and Tkinter that helps users generate secure passwords, store credentials in a JSON database, and quickly retrieve saved login information.

## ✨ Features

* Generate strong random passwords
* Automatic password copy to clipboard using Pyperclip
* Store credentials in a structured JSON database
* Search saved credentials by website name
* Input validation for empty fields
* Exception handling for missing data files
* Clean and user friendly graphical interface
* Default email autofill support

---

## 🖥️ Application Preview

The application allows users to:

1. Enter a website name
2. Enter an email or username
3. Generate a secure password
4. Save credentials to a local JSON database
5. Search previously saved credentials instantly

---

## 🔑 Password Generation

Generated passwords include a random combination of:

* Uppercase letters
* Lowercase letters
* Numbers
* Special symbols

Each password is shuffled to improve randomness and is automatically copied to the clipboard.

---

## 💾 JSON Storage

Credentials are stored in a structured JSON format:

```json
{
    "Google": {
        "email": "example@gmail.com",
        "password": "A8#xP9!kL"
    }
}
```

This makes data easier to manage and retrieve compared to plain text files.

---

## 🔍 Search Functionality

Users can search for a website and instantly retrieve:

* Website name
* Email or username
* Password

If no record exists, the application displays an appropriate message.

---

## 🛠️ Technologies Used

* Python
* Tkinter
* JSON
* Pyperclip

---

## 📁 Project Structure

```text
Password_Manager/
│
├── main.py
├── logo.png
├── data.json
├── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Password_Manager.git
```

Install the required dependency:

```bash
pip install pyperclip
```

Run the application:

```bash
python main.py
```

---
