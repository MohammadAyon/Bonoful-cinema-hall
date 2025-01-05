
# Bonoful Cinema Hall 🎬

Bonoful Cinema Hall is a web-based application designed to provide a seamless experience for movie lovers to explore showtimes, book tickets, and enjoy a modern movie-going experience. The system includes features for users, administrators, and cinema staff to manage bookings, view movies, and handle cinema operations efficiently.

---

## Features

### User Features:
- Browse available movies and showtimes.
- Book tickets online with seat selection.
- View ticket booking history.

### Admin Features:
- Add, update, or remove movies and showtimes.
- Manage ticket bookings.
- View sales and booking reports.

### Additional Features:
- Intuitive and user-friendly interface.
- Secure authentication system for users and admins.
- Real-time seat availability updates.

---

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP, 
- **Database:** MySQL
- **Version Control:** Git and GitHub

---

Installation (Using XAMPP)
Download and Install XAMPP:
Download XAMPP from Apache Friends and install it on your system.

Clone the Repository:
Open your terminal or Git Bash, and run the following command:

bash
Copy code
git clone https://github.com/MohammadAyon/Bonoful-cinema-hall.git
Copy the Project to XAMPP’s htdocs Directory:

bash
Copy code
cp -r Bonoful-cinema-hall C:\xampp\htdocs\
Start Apache and MySQL:
Open the XAMPP control panel and click Start for both Apache and MySQL.

Create the Database:

Open your browser and go to http://localhost/phpmyadmin.
Create a new database (e.g., bonoful_cinema).
Import the provided SQL file (if available) into the newly created database.
Configure the Environment File:

Rename .env.example to .env in the project folder.
Update the following database details:
ini
Copy code
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=bonoful_cinema
DB_USERNAME=root
DB_PASSWORD=
Run the Application:
Open your browser and navigate to:


Copy code
http://localhost/Bonoful-cinema-hall


---

## Usage

1. **User:**  
   Register or log in to the system, browse available movies, select showtimes, and book your tickets.
   
2. **Admin:**  
   Log in to the admin panel to manage movies, showtimes, and bookings. Generate sales and booking reports.

---

## Screenshots



<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/0024cd66-0e4c-4f1f-802e-5c9aedc5ab9b" width="300" /></td>
    <td><img src="https://github.com/user-attachments/assets/19d3d31a-a4f4-44d5-9c1c-3d9d72e7c61b" width="300" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/f4df9a14-afec-4312-a082-6a492cccf96a" width="300" /></td>
    <td><img src="https://github.com/user-attachments/assets/aaf9acc7-b49c-4d73-9139-1de8c43bdde2" width="300" /></td>
  </tr>
</table>



---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contact

For any inquiries or issues, please contact **Mohammad Ayon**:  
- GitHub: [MohammadAyon](https://github.com/MohammadAyon)

---
