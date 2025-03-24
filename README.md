# Flutter Form Validation Project

## Overview
This Flutter project implements a user signup form with validation, navigation, and a success screen with a confetti animation.

## Features
- **Signup Form** with fields for Name, Email, Date of Birth (DOB), and Password.
- **Validation**:
  - Name and Email are required fields.
  - Email is validated using a regex pattern.
  - Password must meet length and complexity requirements.
  - DOB selection is implemented using `FormBuilderDateTimePicker`.
- **Navigation**: The form submits only when all fields are valid and navigates to the success screen.
- **Success Page**: Displays a confirmation message with a confetti effect and a "Go Back" button.

## Technologies Used
- Flutter
- Dart
- `flutter_form_builder` for form validation
- `confetti` package for success animation

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/Ruhisawant/Sign-up-Page-App.git
   cd signup_page
   ```
2. Install dependencies:
   ```sh
   flutter pub get
   ```
3. Run the app:
   ```sh
   flutter run
   ```

Thanks for visiting!