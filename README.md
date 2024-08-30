

# PasswordManager

## Overview

PasswordManager is an Android application designed specifically for senior citizens who may struggle to remember their passwords for banking, online accounts, or any other services. This app provides a secure and user-friendly way to store, manage, and retrieve passwords with a focus on simplicity and high security.

## Features

- **Secure Password Storage**: All passwords are encrypted using AES encryption, ensuring that your sensitive information is kept safe.
- **User-Friendly Interface**: The app is designed with simplicity in mind, featuring a large, easy-to-read interface that is accessible for users of all ages.
- **Master Password Protection**: Access to the app is secured with a master password, which is also encrypted to ensure the highest level of security.
- **Password Management**: Easily add, view, edit, and delete passwords. Passwords are displayed in a list with simple navigation.
- **Auto-Lock Security**: The app automatically locks after a period of inactivity to prevent unauthorized access.
- **Backup and Restore**: (Optional Feature) Securely back up your encrypted passwords to cloud storage or locally and restore them when needed.

## Technology Stack

- **Language**: Java
- **Platform**: Android
- **Database**: SQLite (or SharedPreferences for simple storage)
- **Encryption**: AES (Advanced Encryption Standard)

## How to Use

1. **Setup Master Password**: Upon first launch, you will be prompted to set up a master password. This will be required to access the app in the future.
2. **Add Passwords**: After logging in with your master password, you can add new passwords by clicking the "Add Password" button.
3. **Manage Passwords**: View your saved passwords in a list. Tap on any password entry to edit or delete it.
4. **Auto-Lock**: The app will automatically lock itself after a period of inactivity. You will need to re-enter the master password to regain access.

## Security Features

- **AES Encryption**: All stored passwords are encrypted using AES encryption, one of the most secure encryption standards.
- **Secure Master Password**: The master password is required to access the app and is itself encrypted for added security.
- **Auto-Lock**: Protects against unauthorized access by locking the app after inactivity.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/RutujaMundhe15/PasswordManager.git
   ```
2. Open the project in Android Studio.
3. Build and run the project on your Android device or emulator.

## Contributions

Contributions to this project are welcome. Please fork the repository and submit a pull request for any features or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

