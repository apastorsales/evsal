# EVSAL

EVSAL is a web application designed to bridge the gap between medics and patients, enhancing communication and efficiency within medical agencies. Built using Laravel, EVSAL provides features like appointment scheduling, medical history tracking, and streamlined interaction between patients and healthcare professionals.

---

## Features

### For Patients:
- **Appointment Booking**: Easily schedule appointments with your preferred healthcare professional.
- **Medical History Access**: View your past medical records and treatments.
- **Notifications**: Get reminders for upcoming appointments or follow-up actions.

### For Medics:
- **Appointment Management**: View, accept, or reschedule appointments with patients.
- **Patient Records**: Access comprehensive medical histories within the medical agency.
- **Communication Tools**: Facilitate direct and secure communication with patients.

---

## Tech Stack

### Backend:
- Laravel Framework (PHP)

### Frontend:
- Vue.js

### Database:
- MariaDB

### Other Tools:
- Composer (Dependency Management)
- npm / Yarn (Frontend Asset Management)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/apastorsales/evsal.git
   cd evsal
   ```

2. Install dependencies:
   ```bash
   composer install
   npm install && npm run dev
   ```

3. Set up the environment file:
   ```bash
   cp .env.example .env
   ```
   Update the `.env` file with your database and mail server configuration.

4. Run migrations:
   ```bash
   php artisan migrate
   ```

5. Seed the database (optional):
   ```bash
   php artisan db:seed
   ```

6. Start the development server:
   ```bash
   php artisan serve
   ```

---

## Usage

1. Visit the application at `http://localhost:8000` (or your configured domain).
2. Register as a patient or medic.
3. Explore features such as booking appointments or accessing medical records.

---

## Contact

For questions or feedback, please contact:
- **Email**: pastorsalesalex@gmail.com
- **GitHub**: [apastorsales](https://github.com/apastorsales)

---

Enjoy using EVSAL!

