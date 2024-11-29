Doctor Booking App
This is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) that allows users to book appointments with doctors. It features a user-friendly interface, secure authentication with JWT, and robust form validation with Formik.   

Features
User Roles:

Normal User:
Register/Login with secure authentication.
Upload profile picture (using Cloudinary).
Update profile details (address, gender, contact info).
View hospital/company details.
Browse available doctors and their specializations.
Book appointments with doctors by selecting date and time.
View notifications about appointment bookings.
Manage appointments (view completed and pending appointments).
Apply to become a doctor.


Doctor:
All functionalities of a normal user.
Receive notifications about new appointment requests and application acceptance.
Mark appointments as complete or incomplete.


Admin:
All functionalities of a normal user.
Access to an exclusive admin dashboard.
Manage users (view/remove users).
Manage doctors (view/remove doctors, see salary and specialization details).
Manage appointments (view completed and pending appointments).
Process doctor applications (accept/reject).
Update admin profile.
Technical Details:

Frontend: React.js
Backend: Node.js with Express.js
Database: MongoDB
Authentication: JWT (JSON Web Token)
Form Validation: Formik
Image Upload: Cloudinary
Installation
Clone the repository.
Install dependencies using npm install.
Configure environment variables (database connection string, JWT secret, Cloudinary credentials).
Start the development server using npm start.
Usage
Register an account or Login if you already have one.
As a Normal User, browse doctors, book appointments, and manage your profile.
As a Doctor, manage appointments and view notifications.
As an Admin, access the dashboard to manage users, doctors, and appointments.
Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues.

License
This project is licensed under the MIT License.
