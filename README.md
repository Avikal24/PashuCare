# PahuCare

PashuCare is a web application designed to connect farmers with veterinary doctors for buffaloes and cows. It aims to bridge the gap between rural farmers and accessible veterinary care by providing an easy-to-use platform for consultations and services.

---

## Features
- **Login System**: 
  - Mobile OTP login (using Firebase).
  - Google login as a secondary option.
- **Dashboard**: 
  - Farmers can view available veterinary doctors.
  - Doctors can manage consultation requests.
- **Multilingual Support**: The platform includes Hindi localization for better accessibility.

---

## Tech Stack
- **Frontend**: React.js
- **Backend**: Firebase (Authentication and Database)
- **Deployment**: Vercel (or alternative hosting platform)

---

## Getting Started

### Prerequisites
1. Node.js (v14 or above) installed on your system.
2. Firebase account for backend services.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Avikal24/Pashucare.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Pashucare
   ```

3. Initialize Git (if not already initialized):
   ```bash
   git init
   ```

4. Add the remote repository:
   ```bash
   git remote add origin https://github.com/Avikal24/Pashucare.git
   ```

5. Install dependencies:
   ```bash
   npm install
   ```

6. Configure Firebase:
   - Create a Firebase project.
   - Enable Authentication (Phone and Google sign-in).
   - Replace `firebaseConfig` in the project with your Firebase project credentials.

7. Start the development server:
   ```bash
   npm start
   ```

---

## Folder Structure
```
PashuCare/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── utils/
│   └── App.js
├── .gitignore
├── package.json
├── README.md
└── firebase.js
```

---

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch for your feature/bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---
