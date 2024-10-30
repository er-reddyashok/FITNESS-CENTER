# FITNESS CENTER MANAGEMENT

A web application designed to digitalize and streamline operations within a fitness center. This application, built using Flask, MySQL, and Flask-Mail, enables efficient management of members, trainers, and overall gym operations with automated email notifications for expired memberships.

## Features

- **User Management System**  
  - Administrators and receptionists can add or remove trainers and members.
  - Role-based access for admins, receptionists, and trainers to manage fitness center operations.
  
- **Email Notifications**  
  - Automated email notifications using Flask-Mail to alert users about expired memberships.
  - Helps ensure timely renewals and better user engagement.

- **Database Integration**  
  - All user and membership data are stored in a MySQL database, ensuring secure and efficient data management.

## Tech Stack

- **Backend**: Flask
- **Database**: MySQL
- **Mail Service**: Flask-Mail

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/abhinavmodem/FITNESS-CENTER.git
   cd FITNESS-CENTER
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Database Setup**  
   - Configure MySQL and update the database URI in `config.py`.
   - Run database migrations to set up the required tables.

4. **Run the Application**  
   ```bash
   flask run
   ```

## Usage

- Access the application locally through `http://127.0.0.1:5000`.
- Admins and receptionists can log in to manage trainers and members.
- Users receive automated email notifications regarding membership status.

## License

This project is licensed under the MIT License.
