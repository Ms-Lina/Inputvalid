# Multi-Form Flutter Application

## Overview
This Flutter project is a multi-screen form application that collects user details like **Name, Address, Email, and Phone Number**. The app ensures input validation and proper navigation between screens. The folder structure follows best practices, keeping **main.dart** clean while separating screens into individual files.

## Features
- **Two Screens:** Form Screen and Summary Screen
- **Form Input Fields:** Name, Address, Email, and Phone Number
- **Validation:** Ensures fields are correctly filled with proper error messages
- **Navigation:** Moves between screens smoothly using Flutter’s `Navigator`
- **Responsive UI:** Adaptive design for various screen sizes

## Folder Structure
project_root/
│-- lib/
│   │-- main.dart
│   │-- form_screen.dart
│   │-- summary_screen.dart
│   │-- widgets/
│   │   │-- custom_text_field.dart
│-- pubspec.yaml
│-- README.md
```

## Installation
1. **Clone the Repository**
   ```sh
   git clone https://github.com/Ms-Lina/Inputvalid.git
   cd flutter-multi-form
   ```
2. **Install Dependencies**
   ```sh
   flutter pub get
   ```
3. **Run the Application**
   ```sh
   flutter run
   ```

## Usage
1. Fill out the form fields on the first screen.
2. Submit the form to navigate to the **Summary Screen**.
3. Review the entered data; go back if necessary.

## Input Validation Rules
- **Name:** Cannot be empty (Minimum 3 characters required)
- **Email:** Must follow the valid email format
- **Phone Number:** Only numbers allowed (Minimum 10 digits)
- **Address:** Cannot be empty

## Navigation Flow
- **Form Screen → Summary Screen:** If all fields are valid, the user can navigate forward.
- **Summary Screen → Back to Form Screen:** User can go back and edit details if needed.

## Dependencies
This project uses Flutter’s built-in widgets and `form` validation techniques. No external validation packages are required.

## License
This project is open-source under the **MIT License**.

## Author
By Lina IRATWE
```

