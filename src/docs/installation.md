
# Installation Guide

This guide will walk you through the setup and installation process for the **Password Manager with Biometric Authentication** project.

---

## Prerequisites
Ensure you have the following installed on your system:

1. **Python**
   - Version: Python 3.8 or higher
   - [Download Python](https://www.python.org/downloads/)

2. **Git**
   - To clone the repository and manage version control.
   - [Download Git](https://git-scm.com/)

3. **Pip**
   - Comes pre-installed with Python for managing dependencies.
   - Check your version: `pip --version`

4. **Virtual Environment (optional)**
   - Recommended to isolate project dependencies.
   - Install virtual environment module:
     ```bash
     pip install virtualenv
     ```

---

## Step-by-Step Installation

### 1. Clone the Repository
Clone the project repository from GitHub to your local machine:

```bash
git clone https://github.com/your-username/password-manager-biometric-auth.git
```

Navigate to the project directory:

```bash
cd password-manager-biometric-auth
```

### 2. Set Up a Virtual Environment (Recommended)
Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment:

- On Windows:
  ```bash
  .\venv\Scripts\activate
  ```
- On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

### 3. Install Dependencies
Install the required Python libraries from the `requirements.txt` file:

```bash
pip install -r docs/requirements.txt
```

### 4. Install Additional Tools (Optional)
Some tools may need separate installations:

- **Selenium WebDriver**: Download the driver for your preferred browser (e.g., ChromeDriver for Google Chrome).
  - [ChromeDriver](https://sites.google.com/chromium.org/driver/)
  - Place the driver in your PATH or project directory.

- **Figma**: Use the [Figma desktop app](https://www.figma.com/) for design prototyping.

- **Postman**: Download the [Postman app](https://www.postman.com/) for API testing.

### 5. Run the Application
To start the application, run the GUI module:

```bash
python src/gui/app_ui.py
```

If the GUI opens without errors, the setup is complete!

---

## Troubleshooting

- **Virtual Environment Activation Error**:
  - Ensure your Python installation is added to your system PATH.
  - Reinstall Python with the option to add it to the PATH.

- **Dependency Installation Issues**:
  - Upgrade pip:
    ```bash
    pip install --upgrade pip
    ```

- **GUI Not Displaying**:
  - Ensure PyQt/Tkinter is installed correctly:
    ```bash
    pip install pyqt5
    ```

- **Browser Driver Not Found (Selenium)**:
  - Ensure the browser driver (e.g., ChromeDriver) is in your PATH.

---

## Next Steps
After successfully installing and running the application, explore the following:

- Add biometric authentication methods (facial recognition and fingerprint scanning).
- Test the multi-factor authentication (MFA) using PyOTP.
- Customize the GUI to your liking.

For additional help, refer to the project documentation or contact the team.

