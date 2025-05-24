# 🔐 Python GUI Login System with Encryption

A desktop-based login/signup application built using **Tkinter** with integrated **encryption and decryption** functionality. This project simulates a secure system with database-backed user authentication and encrypted data handling.

## 🚀 Features

- 🔒 User Signup and Login Interface
- 🗝️ Password Encryption and Decryption Logic
- 🖼️ Modern GUI with custom graphics
- 🛡️ MySQL Database Integration for storing credentials
- 🧠 Password reset functionality
- 🧰 Built with Python, Tkinter, MySQL, PIL

## 📸 Preview

> (Insert screenshots here: login screen, sign-up screen, encryption window)

## 🗃️ Project Structure

```
Senior-Project-main/
├── Encryption_Decryption.py     # Cipher logic with GUI
├── signin.py                    # Login page
├── signup.py                    # Registration page
├── *.png / *.jpg                # UI graphics and icons
```

## 🧪 Getting Started

### Prerequisites

- Python 3.x
- MySQL Server
- Python Libraries:
  - `tkinter`
  - `pymysql`
  - `PIL (pillow)`

### Installation

```bash
git clone https://github.com/JoshuaHarlee/Senior-Project.git
cd Senior-Project
```

1. **Start MySQL server** and create a database named `userdata`.
2. Create a table:
```sql
CREATE TABLE data (
    id INT AUTO_INCREMENT PRIMARY KEY,
    email VARCHAR(50),
    username VARCHAR(50),
    password VARCHAR(50)
);
```
3. **Run `signup.py`** to register a new user.

### Run the app

```bash
python signin.py
```

## 📚 Learnings

- GUI application development with Python
- Data security basics (encryption/decryption)
- Backend database interaction using SQL
- Error handling and user experience (UX) design

## 💡 Future Improvements

- Use hashed passwords (e.g., bcrypt) instead of shift cipher
- Add 2FA or email verification
- Dockerize the app for easier deployment
- Store encrypted notes or files, not just credentials

## 📬 Contact

**Joshua Harlee**  
[GitHub](https://github.com/JoshuaHarlee)
