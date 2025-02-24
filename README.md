# **Online Voter Application using PHP and MySQL**  

## **Introduction**  
The **Online Voter Application** is a **PHP-based** web application designed to make the voting process **secure, efficient, and accessible**. This system eliminates traditional paper-based voting and ensures a **transparent and fair** election process.  

## **Features**  
✅ User Registration and Login  
✅ Admin Panel for Election Management  
✅ Candidate Registration and Management  
✅ Secure Voting Mechanism  
✅ Real-time Vote Counting System  
✅ User Authentication and Authorization  
✅ Database Backup and Management  

## **Technologies Used**  
- **Backend**: PHP  
- **Frontend**: HTML, CSS, JavaScript (Bootstrap)  
- **Database**: MySQL  
- **Web Server**: Apache (XAMPP/WAMP)  

## **Installation Guide**  

### **Prerequisites**  
Ensure you have the following installed:  
- **XAMPP/WAMP Server**  
- **PHP (Version 7.4 or later)**  
- **MySQL Database**  

### **Steps to Install**  
1️⃣ **Download and install XAMPP/WAMP**.  
2️⃣ **Clone this repository** or download the project files.  
3️⃣ **Copy the project folder** into the `htdocs` directory (for XAMPP) or `www` (for WAMP).  
4️⃣ **Start Apache and MySQL** from the XAMPP/WAMP Control Panel.  
5️⃣ **Open phpMyAdmin** (`http://localhost/phpmyadmin/`).  
6️⃣ **Create a new database** (e.g., `online_voter`).  
7️⃣ **Import the provided `database.sql` file** into the database.  
8️⃣ **Configure the database connection** in `config.php`:  

```php
<?php
$host = "localhost";
$user = "root";
$password = "";
$database = "online_voter";
$conn = mysqli_connect($host, $user, $password, $database);
if (!$conn) {
    die("Connection failed: " . mysqli_connect_error());
}
?>
```  

9️⃣ **Open your browser** and go to `http://localhost/online-voter/`.  

## **Usage**  

### **Admin Panel**  
🔹 Admin can add/update/delete candidates.  
🔹 Admin can monitor votes in real time.  
🔹 Admin can set up new elections.  

### **Voter**  
🔹 Users can register and log in.  
🔹 Users can vote for their preferred candidate.  
🔹 Users can view election results after voting.  

## **Security Features**  
🔒 **Password hashing** for secure authentication.  
🔒 **SQL injection protection** to prevent hacking attempts.  
🔒 **Secure session management** for safe user access.  

## **Future Enhancements**  
🚀 OTP-based authentication for voters.  
🚀 Integration of blockchain for enhanced security.  
🚀 Email notifications for voter confirmation.  

## **License**  
📜 This project is **open-source** and free to use under the **MIT License**.  

## **Contributing**  
💡 If you find any issues or want to improve the system, feel free to **fork the repository** and submit a **pull request**.  

## **Contact**  
📧 **Email**: [nileshghavate11@gmail.com](mailto:nileshghavate11@gmail.com)  
🔗 **LinkedIn**: [linkedin.com/in/nileshghavate-203b27251](https://linkedin.com/in/nileshghavate-203b27251)  

---

### **🎉 Happy Voting! 🗳️**  
