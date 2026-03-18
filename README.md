# 🔐 Password Manager (Python Tkinter)

A **secure and user-friendly Password Manager desktop application** built with **Python and Tkinter**.

This application allows users to **generate strong passwords**, **store credentials**, and **retrieve saved login details** using a simple graphical interface.

It uses a **JSON-based local database** to persist user data.

## Image
<img width="502" height="429" alt="image" src="https://github.com/user-attachments/assets/d07a96fa-e69e-4cca-89bb-ff488acac1e5" />


## Features

- 🔑 Random secure password generator
- 💾 Save login credentials (Website, Email, Password)
- 🔍 Search saved credentials by website
- ⚠️ Input validation and error handling
- 📂 JSON-based data storage
- 🖥 Clean and intuitive GUI with Tkinter

---

## Technologies Used

- Python 3
- Tkinter (GUI)
- JSON (data storage)
- Random module

---

## 📂 Project Structure

```bash
Password-Manager/
│
├── password-manager/
│   ├── main.py              # Main application file
│   └── logo.png            # Application logo image
│
├── data.json           # Stored passwords (auto-created if missing)
│
└── README.md
```

---

## Requirements

Make sure Python is installed:

```bash
python --version
```

Tkinter is included with Python by default.

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/adebayoadesugba/password-manager.git
```

### Navigate to Project Folder

```bash
cd Password-Manager/password-manager
```

### Run the Application

```bash
python main.py
```

---

## How to Use

1. Enter a **Website name**
2. Enter your **Email/Username**
3. Click **Generate Password** (optional)
4. Click **Add Password** to save

#### To Search for a Password:
- Enter the website name
- Click **Search**
- Saved credentials will be displayed

---

## How It Works

- Passwords are stored in a JSON file:

```json
{
    "Amazon": {
        "Email": "user@example.com",
        "Password": "securepassword123"
    }
}
```

- Data is:
  - Loaded from `data.json`
  - Updated dynamically
  - Created automatically if file does not exist

---

## Error Handling

The application handles:

- Missing JSON file (`FileNotFoundError`)
- Empty input fields
- Non-existing website searches

---

## Security Note

- This app stores passwords **locally in plain text (JSON)**  
- It is intended for **learning and demonstration purposes only**

#### Future security improvements:
- Encrypt stored passwords
- Add master password authentication
- Use secure vault systems

---

## Future Improvements

- Password encryption (e.g., hashing or AES)
- Copy password to clipboard
- Password strength indicator
- Dark mode UI
- Cloud sync support

---

## Key Concepts Learned

- GUI development with Tkinter
- File handling with JSON
- Exception handling (`try/except`)
- Data persistence
- Modular programming

---

## Author

**Adebayo Adesugba**

- Full Stack Developer  
- Python | JavaScript | React | Node.js | AI Development  

---

## ⭐ Support

If you found this project useful:

- ⭐ Star the repository  
- 🍴 Fork it  
- 🧑‍💻 Contribute  

---

## License

This project is open-source and available under the **MIT License**.
