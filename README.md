# Bus Management System

Welcome to the Bus Management System – a comprehensive solution for managing bus inquiries and bookings. This system is designed to offer a smooth experience for both users and administrators, providing efficient bus tracking and management functionalities. 

## Features
- User Login: Users can log in to browse, inquire, and book buses.
- Admin Login: Administrators have access to manage bus schedules, routes, and bookings.
- Bus Inquiry: Users can search for available buses by route, date, and time.
- Bus Booking: Simple and easy-to-use interface for booking buses.
- Database Integration: All data related to buses, bookings, and users is securely managed through a MySQL database.

## Stack Used
- Frontend: React JS (Located in the `Frontend` folder)
- Backend: Node JS, Express JS (Located in the `Backend` folder)
- Database: MySQL

## Getting Started

### Prerequisites
Before you start, ensure you have the following installed on your machine:
- Node.js (v12 or higher)
- MySQL database
- npm (Node package manager)

### Installation

1. Fork and Clone the Repository  
   Start by forking and cloning the repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/Bus-Management-System.git
   ```

2. Install npm modules  
   Navigate to both the `Frontend` and `Backend` folders, and install the necessary npm modules.

   ```bash
   cd Frontend
   npm install
   ```

   ```bash
   cd Backend
   npm install
   ```

3. Configure the Database  
   In the `server.js` file located in the `Backend` folder, update the connection details to match your MySQL database credentials.

   ```js
   const connection = mysql.createConnection({
       host: 'your-host',
       user: 'your-username',
       password: 'your-password',
       database: 'bus_management'
   });
   ```

4. Execute Database Commands  
   Use the commands provided in the `Database.txt` file to set up the required tables in your MySQL database.

5. Run the Application  
   Once everything is set up, you can run the server. Open a terminal, navigate to the `Backend` folder, and type the following command:

   ```bash
   node server.js
   ```

   This will start the server on the default port `3000`.

6. Access the App  
   Open your browser and go to `http://localhost:3000` to access the Bus Management System.

## Folder Structure

- Frontend: Contains all React JS code for the client-side interface.
- Backend: Contains all Node JS and Express JS code for server-side functionalities.
- Database.txt: SQL commands to create the necessary tables for the application.

## Future Enhancements
- Real-time bus tracking
- SMS/email notification system for bookings
- Payment gateway integration for online bookings

## Contribution
Feel free to fork the project, open issues, and submit pull requests. We welcome contributions to make the system more robust and feature-rich.

## License
This project is open-source and available under the MIT License. 

Feel free to contact me in case of any help needed!
