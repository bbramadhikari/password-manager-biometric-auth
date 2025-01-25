# Password Manager with Biometric Authentication

## Overview

This project is a **Password Manager** that integrates **biometric authentication** for enhanced security. The system includes:

- Facial recognition (using **OpenCV**)
- Fingerprint scanning (using **PyFingerprint**)
- Password encryption and storage (using **PyCrypto** and **Cryptography**)
- Multi-factor authentication (using **PyOTP** for TOTP generation)

Additionally, it provides a user-friendly **Graphical User Interface (GUI)** designed with **PyQt/Tkinter** and styled using **Material UI**. The project prioritizes security by incorporating **penetration testing tools** and advanced machine learning capabilities for facial recognition using **TensorFlow**.

---

## Features

### 1. **Authentication**

- **Facial Recognition:** Users authenticate by scanning their faces.
- **Fingerprint Scanning:** Verifies a user's fingerprint to unlock the password vault.
- **Multi-Factor Authentication:** Adds an extra layer of security by requiring a time-based OTP.

### 2. **Encryption**

- Passwords are stored in encrypted form using **AES encryption** for maximum security.
- The system uses both **PyCrypto** and **Cryptography** libraries for secure encryption and decryption.

### 3. **User Interface**

- A modern GUI built with **PyQt/Tkinter**.
- Clean, responsive design using **Material UI**.

### 4. **Testing and Validation**

- Automated unit testing with **PyTest**.
- GUI testing across browsers and devices using **Selenium**.
- API testing and validation using **Postman**.
- Security testing with penetration testing tools.

### 5. **Prototyping and Design**

- The app's design is prototyped using **Figma** for better usability.

---

## Project Structure

```
password-manager-biometric-auth/
├── src/
│   ├── authentication/
│   │   ├── facial_recognition.py   # Handles facial recognition
│   │   ├── fingerprint_scanner.py  # Handles fingerprint scanning
│   │   └── mfa.py                  # Multi-factor authentication (TOTP)
│   ├── encryption/
│   │   ├── encryptor.py            # Encrypts passwords
│   │   └── decryptor.py            # Decrypts passwords
│   ├── gui/
│   │   ├── app_ui.py               # Main GUI code
│   │   ├── themes/                 # Material UI themes
│   └── tests/
│       ├── test_authentication.py  # PyTest scripts for authentication
│       ├── test_gui.py             # Selenium GUI tests
│       └── test_api.py             # API tests
├── prototypes/
│   ├── design.fig                  # Figma design file
│   └── screenshots/                # Screenshots of prototypes
├── docs/
│   ├── requirements.txt            # Python dependencies
│   ├── installation.md             # Setup instructions
│   └── architecture.md             # System architecture
├── .gitignore                      # Git ignored files
├── LICENSE                         # License (if applicable)
└── README.md                       # Main project documentation
```

---

## Tools Used

| Tool                      | Purpose                                                |
| ------------------------- | ------------------------------------------------------ |
| **OpenCV**                | Facial recognition for user authentication             |
| **PyFingerprint**         | Fingerprint scanning for secure access                 |
| **PyCrypto**              | Encrypt passwords securely using AES encryption        |
| **Cryptography**          | Adds additional encryption and decryption capabilities |
| **PyOTP**                 | Enables multi-factor authentication via TOTP           |
| **PyTest**                | Unit testing for individual modules                    |
| **Selenium**              | UI testing across browsers and devices                 |
| **Postman**               | API testing and validation                             |
| **PyQt/Tkinter**          | GUI development                                        |
| **Material UI**           | Enhances the GUI with modern styles                    |
| **Figma**                 | Prototyping and designing the app                      |
| **TensorFlow** (optional) | Enhances facial recognition with machine learning      |
| **Jira**                  | Task management and project tracking                   |

---

## Getting Started

### Prerequisites

1. Python 3.8 or higher.
2. Install the required dependencies:
   ```bash
   pip install -r docs/requirements.txt
   ```

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/password-manager-biometric-auth.git
   ```
2. Navigate to the project directory:
   ```bash
   cd password-manager-biometric-auth
   ```
3. Run the application:
   ```bash
   python src/gui/app_ui.py
   ```

---

## Contributing

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your commit message here"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request for review.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact

For any questions or support, reach out to:

- **Name:** Baburam Adhikari
- **Email:** psnbabu5@gmail.com
- **GitHub:** https://github.com/bbramadhikari





