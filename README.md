This is a repository of projects for the slash internship. It was created by Hani Al Soufi.

Task 1
A simple Python command-line tool to encrypt and decrypt text using AES-256 encryption.

Requirements
Python 3.x
Install the required library: pip install cryptography
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/text-encryption-tool.git
cd text-encryption-tool
Run the script:

bash
Copy code
python encrypt_decrypt.py
Choose an option:

Option 1: Encrypt text
Option 2: Decrypt text
Example:

bash
Copy code
=== Text Encryption/Decryption ===
1. Encrypt Text
2. Decrypt Text
3. Exit
Enter your choice (1/2/3): 1
Enter the text to encrypt: Hello, world!
Encrypted Text: mEOVxWlc1Vj3dTSTQR2iBw==
License
MIT License.

Task 2

This is a simple Python-based keylogger that records every keystroke typed on the keyboard. The keystrokes are saved to a text file called key_log.txt in the same directory as the script.

Prerequisites
Python 3.x
pynput library (used to capture keyboard events)
Installation
Install Python 3.x from Python's official website if you don't already have it installed.
Install the pynput library using pip:
bash
Copy code
pip install pynput
How to Run
Download or copy the keylogger script.
Open a terminal or command prompt in the same directory as the script.
Run the script using Python:
bash
Copy code
python keylogger.py
The keylogger will now record any keystrokes and save them in the key_log.txt file.
To stop the keylogger, press the esc key.
Key Points
Output File: The keystrokes are saved in a file named key_log.txt.
Stop Keylogger: Press esc to stop the program.
Important Notes
This software is for educational purposes only. Make sure you have permission before recording anyone’s keystrokes. Misuse of keylogger software is illegal and unethical. Always comply with privacy laws and obtain proper authorization before running this on any system.

Task 3

This Python script allows you to encrypt and decrypt image files using AES (Advanced Encryption Standard) with a secure password.

Requirements:
Python 3.x
cryptography library
Installation:
Install Python dependencies:
bash
Copy code
pip install cryptography
Usage:
Encrypt an image:

python
Copy code
encrypt_image('path_to_your_image.jpg', 'your_secure_password')
This will create an encrypted file named path_to_your_image.jpg.enc.

Decrypt an image:

python
Copy code
decrypt_image('path_to_your_image.jpg.enc', 'your_secure_password', 'decrypted_image.jpg')
This will decrypt the file and save it as decrypted_image.jpg.

Example:
To encrypt:

python
Copy code
encrypt_image('image.jpg', 'my_password')
To decrypt:

python
Copy code
decrypt_image('image.jpg.enc', 'my_password', 'output.jpg')
Notes:
Use a strong password for encryption.
Do not lose the password, as it’s required for decryption.
License:
Feel free to use and modify the code as needed.
