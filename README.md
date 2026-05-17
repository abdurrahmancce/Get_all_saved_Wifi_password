# 📶 Wi-Fi Profile Auditor

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

A professional Python utility for auditing and displaying saved Wi-Fi profiles on Windows systems for authorized network administration, diagnostics, and educational purposes.

</div>

---

# 📑 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Usage](#-usage)
- [Example Output](#-example-output)
- [How It Works](#-how-it-works)
- [Security & Ethics](#-security--ethics)
- [Use Cases](#-use-cases)
- [Future Improvements](#-future-improvements)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

# 📖 Overview

**Wi-Fi Profile Auditor** is a lightweight and efficient command-line utility built with Python that retrieves and displays saved wireless network profile names stored on a Windows machine.

The project is designed for:

- Network diagnostics
- IT administration
- Educational demonstrations
- System auditing
- Learning Windows networking automation

The tool leverages the built-in Windows `netsh` command through Python's `subprocess` module to collect and format profile information in a clean and readable output.

---

# ✨ Features

## 🔹 Core Features

- 📡 Display saved Wi-Fi profile names
- ⚡ Fast execution with minimal resource usage
- 🖥️ Native Windows command integration
- 🧹 Clean formatted terminal output
- 🧠 Beginner-friendly code structure
- 🔒 Safe auditing-focused implementation

## 🔹 Developer Features

- Simple Python architecture
- Easy to customize and extend
- No third-party dependencies required
- Well-commented and readable logic

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python 3 | Core programming language |
| subprocess | Execute Windows commands |
| netsh | Windows network management utility |
| Command Prompt | Terminal interaction |

---

# 📂 Project Structure

```bash
wifi-profile-auditor/
│
├── main.py
├── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/wifi-profile-auditor.git
```

---

## 2️⃣ Navigate to the Project Directory

```bash
cd wifi-profile-auditor
```

---

## 3️⃣ Verify Python Installation

```bash
python --version
```

Expected Output:

```bash
Python 3.8+
```

---

# ▶️ Usage

Run the script directly from the terminal:

```bash
python main.py
```

---

# 💻 Example Output

```bash
========================================
      SAVED WI-FI PROFILE AUDITOR
========================================

Wi-Fi Profiles Found:

Home_Network
Office_WiFi
Android_Hotspot
University_Network

========================================
Scan Completed Successfully
========================================
```

---

# ⚡ How It Works

The application performs the following steps:

1. Executes the Windows command:

```bash
netsh wlan show profiles
```

2. Retrieves all stored wireless profile names from the system.

3. Parses the command-line output using Python string operations.

4. Displays the results in a formatted terminal interface.

---

# 🔒 Security & Ethics

This project is intended strictly for:

- Educational purposes
- Authorized device diagnostics
- Personal network auditing
- IT administration on owned systems

## ❗ Important Notice

Do not use this project on systems, devices, or networks without explicit authorization.

Unauthorized access or misuse may violate laws, organizational policies, or ethical guidelines.

---

# 🎯 Use Cases

- Learning Python automation
- Understanding Windows networking commands
- Cybersecurity lab demonstrations
- IT troubleshooting
- Wireless network inventory audits
- Educational programming projects

---

# 🚀 Future Improvements

Planned enhancements for future releases:

- GUI version using Tkinter or PyQt
- Export profiles to TXT/CSV
- Wireless adapter information
- Real-time network scanning
- Cross-platform support
- Logging system
- Colored terminal UI

---

# 🤝 Contributing

Contributions are welcome and appreciated.

## Contribution Steps

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this software in accordance with the license terms.

---

# 👨‍💻 Author

## Abdur Rahman

Python Developer • Cybersecurity Enthusiast • Open Source Learner

### Connect With Me

- GitHub: https://github.com/abdurrahmancce
- LinkedIn: https://www.linkedin.com/in/abdur-rahman-akash-60450b2aa
- Email: akash.abdur.2002@gmail.com

---

# ⭐ Support

If you found this project useful:

- Give the repository a ⭐
- Share it with others
- Contribute improvements
- Report issues

---

<div align="center">

### 💙 Thank You for Visiting This Project

Made with Python & Passion 🚀

</div>
