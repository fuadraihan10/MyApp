# MyApp 🚀

A modern authentication system built with Python and Tkinter, featuring a sleek user interface and secure user management.

## Features ✨

- 🔐 User Authentication System
  - Secure login and registration
  - Password reset functionality
  - Email verification system
  - Password visibility toggle
  
- 📱 Modern UI Elements
  - Animated GIF background
  - Social media login buttons (Google, Facebook)
  - Clean and intuitive interface
  - Eye-catching design elements

- 🛡️ Security Features
  - Email verification for new registrations
  - Email confirmation for password reset
  - Secure password storage
  - Input validation

## Prerequisites 📋

- Python 3.x
- Required Python packages (see requirements.txt)

## Installation 🔧

1. Clone the repository
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Ensure all assets are in the "Assets" folder:
   - closed_eye.png
   - open_eye.png
   - facebook.png
   - google.png
   - gif.gif
   - icon.png

## Requirements.txt 📝

```
Pillow==10.2.0
openpyxl==3.1.2
```

## File Structure 📁

```
MyApp/
│
├── Assets/
│   ├── closed_eye.png
│   ├── open_eye.png
│   ├── facebook.png
│   ├── google.png
│   ├── gif.gif
│   └── icon.png
│
├── MyApp.py
├── requirements.txt
├── user_data.xlsx
└── README.md
```

## Usage 💻

1. Run the application:
   ```bash
   python MyApp.py
   ```
2. The application will start with the login page
3. New users can register by clicking "Create new one"
4. Existing users can:
   - Login with their credentials
   - Reset password if forgotten
   - Toggle password visibility

## Security Notes 🔒

- Passwords are stored in an Excel file
- Email verification is required for:
  - New account registration
  - Password reset
- Input validation is implemented for:
  - Email format
  - Password matching
  - Empty fields

## Contributing 🤝

Feel free to fork the project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License 📄

This project is licensed under the MIT License - see the LICENSE file for details..

## Acknowledgments 🙏

- Icons from [Assets folder]
- UI inspiration from modern authentication systems