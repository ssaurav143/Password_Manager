# 🔐 Password Manager

A simple and secure Password Manager application built using Python Tkinter.

The application allows users to generate strong random passwords, copy them automatically to the clipboard, and save website login credentials locally using a clean graphical interface.

---

## 🎮 Features

- Random strong password generation  
- Automatic clipboard copy using Pyperclip  
- Save website credentials locally  
- User confirmation popup before saving  
- Input validation for empty fields  
- Clean and beginner friendly GUI  
- Default email autofill support  

---

## 🧠 How It Works

- Enter website name  
- Enter email or username  
- Generate a secure password  
- Click the Add button to save credentials  

Saved credentials are stored inside:

```text
data.txt
```

---

## ▶️ How to Run

1. Install Python  
2. Install Pyperclip  

```bash
pip install pyperclip
```

3. Run the application  

```bash
python main.py
```

---

## 📁 Project Structure

```text
Password_Manager/
│
├── main.py
├── logo.png
├── data.txt
```

---

## 🛠️ Tech Used

- Python  
- Tkinter  
- Pyperclip  

---

## 🔐 Password Generation Logic

The generated password contains:

- Random uppercase and lowercase letters  
- Random numbers  
- Random symbols  

The password is shuffled for better security.
## 📌 Author

Made by Satya 😄
