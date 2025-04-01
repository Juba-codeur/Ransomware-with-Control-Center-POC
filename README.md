# README - Ethical Ransomware Project

## Overview
This project is a **proof of concept (PoC) ransomware** developed It is designed strictly for **educational and research purposes** to demonstrate how ransomware operates and how security professionals can protect against it.

## Features
- **AES Encryption:** Uses the AES algorithm to encrypt targeted files securely.
- **Machine Identification:** Generates a unique machine ID for tracking.
- **GUI Implementation:** Displays a ransomware message via a Tkinter-based graphical user interface.
- **Networking:** Communicates with a remote server to send encryption keys.
- **Persistence Mechanisms:** Ensures the ransomware remains active even after a restart.
- **Decryption Panel:** Allows users to enter a key and decrypt files if they have the correct passcode.

## Ethical Considerations
This project is intended solely for **ethical hacking training and cybersecurity research**. Deploying ransomware in unauthorized environments is illegal and punishable under cybersecurity laws. Always use such scripts in a **controlled, isolated environment**.

## Components
### 1. Ransomware Script (`rans.py`)
- Encrypts files using AES encryption.
- Sends encryption keys to a remote server.
- Ensures persistence and displays a ransom note via GUI.

### 2. GUI Application (`gui.py`)
- Uses Tkinter to create a user-friendly decryption panel.
- Displays the ransom message and instructions.
- Accepts a decryption key input from the user.
- Logs activity and updates a progress bar during decryption.

### 3. Encryption Script (`Simple-Encryption.py`)
- Uses AES encryption in CBC mode.
- Derives a key from a hardcoded password.
- Encrypts files and removes the original version.
- Ensures files can only be recovered with the correct decryption key.

## Setup and Execution (For Educational Purposes Only)
### Installation
1. **Install Dependencies:**
   ```sh
   pip install pycryptodome pillow
   ```
2. **Run the Ransomware Script:**
   ```sh
   python rans.py
   ```
3. **Launch the GUI Application:**
   ```sh
   python gui.py
   ```

### Testing File Encryption
1. Place a test file (e.g., `test.txt`) in the working directory.
2. Run `Simple-Encryption.py` to encrypt the file.
3. Use `gui.py` to attempt decryption with the correct key.

## Decryption Process (PoC)
A corresponding decryption mechanism is included for **ethical research purposes**. Users can test decrypting the files using a provided key.

## Legal Disclaimer
This project is for **educational use only**. The author and instructors are **not responsible for any misuse** of this script. Unauthorized deployment of ransomware can lead to severe legal consequences.

## Learning Outcomes
- Understanding ransomware attack vectors.
- Learning how encryption works in real-world malware.
- Developing countermeasures against ransomware threats.
- Enhancing penetration testing and ethical hacking skills.

---
**Use responsibly. Stay ethical. Protect systems.**

# Ransomware-with-Control-Center-POC
