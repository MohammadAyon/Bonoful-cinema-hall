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
- **Backend:** PHP 
- **Database:** MySQL
- **Version Control:** Git and GitHub

---

## Installation (Using XAMPP)

1. **Download and Install XAMPP:**  
   Download XAMPP from [Apache Friends](https://www.apachefriends.org/index.html) and install it on your system.

2. **Clone the Repository:**  
   Open your terminal or Git Bash, and run the following command:
   ```bash
   git clone https://github.com/MohammadAyon/Bonoful-cinema-hall.git
   ```

3. **Copy the Project to XAMPP’s `htdocs` Directory:**  
   ```bash
   cp -r Bonoful-cinema-hall C:\xampp\htdocs\
   ```

4. **Start Apache and MySQL:**  
   Open the XAMPP control panel and click **Start** for both Apache and MySQL.

5. **Create the Database:**  
   - Open your browser and go to `http://localhost/phpmyadmin`.
   - Create a new database (e.g., `bonoful_cinema`).
   - Import the provided SQL file (if available) into the newly created database.

6. **Configure the Environment File:**  
   - Rename `.env.example` to `.env` in the project folder.
   - Update the following database details:
     ```ini
     DB_CONNECTION=mysql
     DB_HOST=127.0.0.1
     DB_PORT=3306
     DB_DATABASE=bonoful_cinema
     DB_USERNAME=root
     DB_PASSWORD=
     ```

7. **Run the Application:**  
   Open your browser and navigate to:
   ```
   http://localhost/Bonoful-cinema-hall
   ```

---

### UI Preview


<div style="display: flex; flex-wrap: wrap; gap: 10px;">

  <div style="flex: 1 1 calc(50% - 10px);">
      <img src="https://github.com/user-attachments/assets/0024cd66-0e4c-4f1f-802e-5c9aedc5ab9b" alt="Front UI" width="100%">
      <p align="center"><b>Front UI</b></p>
  </div>

  <div style="flex: 1 1 calc(50% - 10px);">
      <img src="https://github.com/user-attachments/assets/19d3d31a-a4f4-44d5-9c1c-3d9d72e7c61b" alt="Booking" width="100%">
      <p align="center"><b>Booking</b></p>
  </div>

  <div style="flex: 1 1 calc(50% - 10px);">
      <img src="https://github.com/user-attachments/assets/f4df9a14-afec-4312-a082-6a492cccf96a" alt="Admin" width="100%">
      <p align="center"><b>Admin</b></p>
  </div>

  <div style="flex: 1 1 calc(50% - 10px);">
      <img src="https://github.com/user-attachments/assets/aaf9acc7-b49c-4d73-9139-1de8c43bdde2" alt="Movie List Admin" width="100%">
      <p align="center"><b>Movie List Admin</b></p>
  </div>

</div>



## Usage

1. **User:**  
   Register or log in to the system, browse available movies, select showtimes, and book your tickets.
   
2. **Admin:**  
   Log in to the admin panel to manage movies, showtimes, and bookings. Generate sales and booking reports.



---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contact

For any inquiries or issues, please contact **Mohammad Ayon**:  
- GitHub: [MohammadAyon](https://github.com/MohammadAyon)

---
