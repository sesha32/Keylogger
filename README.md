# Keylogger Project

## Overview

This project is a **Keylogger** built using Python, designed for educational purposes to understand the fundamentals of cybersecurity and ethical hacking. Keyloggers are tools that capture keystrokes made on a keyboard, and they are commonly used in cybersecurity training to highlight vulnerabilities and promote awareness about securing systems.

**⚠️ Disclaimer:**  
This project is strictly for **educational purposes** and should not be used for unethical or illegal activities. Always obtain proper permissions before deploying this tool in any environment.

---

## Features

- **Keystroke Logging:** Captures all keystrokes typed on the keyboard.
- **Log Storage:** Saves the captured keystrokes in a log file for review.
- **Customizable Behavior:** Can be configured for various logging durations and outputs.
- **Cross-Platform Support:** Runs on multiple operating systems with Python installed.

---

## Technologies Used

- **Programming Language:** Python
- **Libraries:** 
  - `pynput` (for capturing keyboard input)
  - `os` and `time` (for additional functionalities)

---

## How It Works

1. The keylogger utilizes the `pynput` library to monitor and record keystrokes.
2. Each keystroke is logged and stored in a text file in the specified location.
3. The program runs in the background, continuously capturing keyboard input until terminated.

---

## Setup and Installation

### Prerequisites
- Python 3.x installed on your system.
- Required Python libraries:
  - Install `pynput` by running:  
    ```bash
    pip install pynput
    ```

### Steps to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/keylogger-project.git
    cd keylogger-project
    ```
2. Open the script file `keylogger.py` in a text editor and configure the output file location for logs.
3. Run the script:
    ```bash
    python keylogger.py
    ```

4. To stop the keylogger, use the `Ctrl + C` command in the terminal or terminate the process.

---

## Ethical Usage

This project was built as part of my **cybersecurity learning journey** during my internship with **IBM SkillsBuild**. It is intended to:
- Demonstrate how keyloggers work.
- Promote awareness of how such tools can be used maliciously.
- Encourage developers to adopt secure coding practices to mitigate such vulnerabilities.

### Key Takeaways:
- Protect your devices by using firewalls, antivirus software, and secure authentication methods.
- Avoid installing unknown software or clicking on suspicious links.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
