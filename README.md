
---

# CryptDeCrypt - Password Manager

<div align="center">
  <br>
      <img src="https://github.com/RJohnPaul/CryptDeCrypt/blob/a047c7dc5028c1c24c4f73e301c189cdbe3e006a/Frame%207.png" alt="Project Banner">
  </br>
</div>

<div align="center">
  <br>
      <img src="https://github.com/RJohnPaul/CryptDeCrypt/blob/3848b5636b76ee1a6f3326550d99547d78f8ff1c/Frame-5(1).png" alt="Project Banner">
  </br>
</div>

<br/>

## Description

CryptDeCrypt is a secure password manager designed to encrypt and manage user passwords. The program utilizes encryption and hashing techniques to ensure the confidentiality and integrity of stored passwords.

## Features

- **Secure Password Storage:** Passwords are encrypted using Fernet symmetric key encryption, and user-specific keys are stored in separate key files.

- **User Authentication:** Users are required to authenticate themselves with a master password before accessing the password manager.

- **Password Strength Check:** The program checks the strength of passwords against predefined criteria, ensuring they meet minimum requirements.

- **SQLite Database:** Passwords and user information are stored in an SQLite database, providing a structured and secure way to manage data.

- **Password History:** The program keeps track of password changes, maintaining a history of encrypted passwords associated with each user.

- **GUI Interface:** The graphical user interface (GUI) is built using Tkinter, providing a user-friendly experience for interacting with the password manager.

## Modules Required

1. **cryptography** - [Cryptography Library](https://cryptography.io/en/latest/)
   - Used for Fernet symmetric key encryption and hashing algorithms.

2. **ttkthemes** - [Themed Tkinter Widgets](https://ttkthemes.readthedocs.io/en/latest/)
   - Provides additional themed styles for Tkinter widgets.

3. **password_strength** - [Password Strength Library](https://pypi.org/project/password-strength/)
   - Used for checking password strength against predefined criteria.

## Requirements

- Python 3.x
- Install required modules: `pip install -r requirements.txt`

## Getting Started

1. Clone the repository: `git clone <repository-url>`
2. Install required modules: `pip install -r requirements.txt`
3. Run the program: `python main.py`
4. Enter your master password to access the password manager.

## Usage

- **Storing Passwords:** Enter the username and password, click "Store Password," and the program will securely store the information.

- **Authenticating Users:** Enter the username and password, click "Authenticate User," and the program will verify the user's credentials.

## Security Considerations

- **Master Password:** Choose a strong master password. The security of your stored passwords heavily depends on the strength of your master password.

- **Backup Key Files:** Store backup copies of your key files in a secure location. Losing these files may result in permanent data loss.

## License

This project is licensed under the [MIT License](LICENSE).

---
