
# HosteLight – Smart Hostel Automation System

HosteLight is a comprehensive web application designed to streamline and automate hostel management processes. Built with Angular, it provides a robust, scalable, and maintainable solution for administrators, wardens, rectors, and students. The system integrates modern UI/UX, advanced state management, and AI-powered features to deliver a seamless experience.

---

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technical Stack](#technical-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview

HosteLight automates hostel operations such as user management, complaint handling, leave approvals, backups, and AI-powered controls. The platform is modular, responsive, and designed for real-world scalability. It supports role-based access control for students, wardens, rectors, and administrators.

---

## Key Features

- **Modular Architecture:** Each module is self-contained for easy maintenance and scalability.
- **Responsive Design:** Fully responsive UI built with Tailwind CSS.
- **State Management:** Utilizes NgRx for predictable and efficient state handling.
- **Advanced Routing:** Powered by Angular Router with lazy loading and route guards.
- **User Management:** Add, approve, block/unblock users with role-based access control.
- **Complaint Management:** Track, manage, and resolve student complaints efficiently.
- **Leave Management:** Multi-level approval workflow for leave requests.
- **AI Integration:** Connect and manage AI APIs for summarization and automated alerts.
- **Backup & Logs:** Export data and download logs for compliance and record-keeping.
- **Unit Testing:** Comprehensive testing using Jasmine and Karma.
- **Firebase Integration:** Authentication, hosting, and real-time database support via Firebase.

---

## Technical Stack

- **Frontend:** Angular (Standalone Components)
- **State Management:** NgRx
- **Routing:** Angular Router
- **Styling:** Tailwind CSS
- **Backend & Hosting:** Firebase
- **Testing:** Jasmine, Karma

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/HosteLight.git
cd HosteLight
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the Development Server

```bash
ng serve
```

### 4. Open in Browser

Visit: [http://localhost:4200](http://localhost:4200)

---

## Usage

* **Admin Dashboard:** Manage users, complaints, AI settings, logs, and backups.
* **Role-Based Dashboards:** Students, wardens, and rectors have customized dashboards.
* **AI Controls:** Configure and manage AI APIs for automation tasks.
* **Logs & Backups:** Download system logs and export structured data.

---

## Project Structure

```
.
├── public/                # Static assets and Firebase hosting files
├── src/
│   ├── app/
│   │   ├── main-app/      # Core layout components (header, footer, layout)
│   │   ├── pages/         # Feature pages (home, users, complaints, dashboard, etc.)
│   │   ├── services/      # Angular services (auth, API, theme, guards, etc.)
│   │   ├── externalpages/ # Loaders, skeletons, and shared UI components
│   │   └── interfaces/    # TypeScript interfaces and models
│   ├── assets/            # Images and static resources
│   └── index.html         # Application entry point
├── angular.json           # Angular CLI configuration
├── firebase.json          # Firebase hosting configuration
├── package.json           # Dependencies and scripts
└── README.md              # Project documentation
```

---

## Contributing

Contributions are welcome. Please follow the steps below:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes.
4. Commit your changes:

   ```bash
   git commit -m "Add: short description of feature"
   ```
5. Push to your branch:

   ```bash
   git push origin feature/your-feature-name
   ```
6. Open a Pull Request.

Ensure your code follows project standards and includes appropriate tests where applicable.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact

For questions, suggestions, or issues, please open an issue on the GitHub repository.

---

© 2026 HosteLight – Smart Hostel Automation System

```
```
