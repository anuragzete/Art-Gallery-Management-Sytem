# Art Gallery Management System (AGMS)

The **Art Gallery Management System (AGMS)** is a PHP-based web application designed to manage and display art pieces in an online gallery. It includes an admin panel for managing artworks, artists, and gallery information.

---

## Live Demo

[Visit My Portfolio](https://agms.infinityfreeapp.com/index.php)

---

## How to Run the Project

### 1. Download the Project
- Download the project zip file and extract it.

### 2. Move the Project Files
- Copy the extracted `agms` folder.
- Paste it into the server's root directory:
    - For **XAMPP**: `xampp/htdocs`

### 3. Set Up the Database
1. Open **PHPMyAdmin** in your browser:  
   `http://localhost/phpmyadmin`
2. Create a new database named:  
   `agmsdb`
3. Import the SQL file:
    - Go to the **Import** tab.
    - Select the `agmsdb.sql` file.
    - Click **Go** to import the database schema and data.

### 4. Run the Application
- Open your browser and visit:  
  `http://localhost/agms`

---

## Admin Panel Credentials

- **Username:** `admin`
- **Password:** `Test@123`

---

## Project Directory Structure
```
/agms                     # Main project folder  
 ├── /admin               # Admin panel files  
 ├── /css                 # CSS stylesheets  
 ├── /images              # Gallery images  
 ├── /includes            # PHP include files for reusability  
 ├── /js                  # JavaScript files  
 ├── /webfonts            # Font files  
 ├── about.php            # About page  
 ├── art-enquiry.php      # Art enquiry form  
 ├── contact.php          # Contact form  
 ├── index.php            # Home page  
 ├── product.php          # Product listing page  
 ├── search.php           # Search functionality  
 ├── single-product.php   # Single product display page  
/SQL File                  # SQL schema folder  
 ├── agmsdb.sql           # Database schema file  
/README.md                 # Project documentation  
```

---

## Technologies Used
- **Backend:** PHP
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript
- **Server:** XAMPP

---

## Troubleshooting
- If you encounter errors:
    - Ensure your **XAMPP** server is running.
    - Verify that the **database name** in your configuration file matches `agmsdb`.
    - Confirm that the correct **port** is being used (default: `80`).

---

## Contact
For any queries or support, feel free to reach out at:  
**[anuragzete27@outlook.com]**

---

## License
This project is licensed under the **MIT License**. Feel free to modify and extend it.

---

Enjoy managing your Art Gallery! 

