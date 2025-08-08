# Online Voting System

**Short description**  
A secure, web-based Online Voting System built with HTML, PHP and MySQL. Features voter authentication, ballot creation, vote casting, and automated result tallying. Designed as a university/college project focused on practical implementation and basic security measures.

---

## Demo / Screenshots
![Login screen](assets/screenshots/login.png)
![Admin panel](assets/screenshots/admin.png)

---

## Features
- Voter registration & authentication
- Admin panel to create elections and ballots
- Secure vote casting and instant tallying
- Basic input validation and database-driven storage
- Exportable results (CSV)

---

## Tech stack
- Frontend: HTML, CSS, JavaScript
- Server-side: PHP
- Database: MySQL
- (Optional) XAMPP/LAMP stack for local testing

---

## Setup (local)
1. Install XAMPP / LAMP / MAMP.
2. Place project folder in the server `htdocs/` (or equivalent).
3. Import database schema:
   - Use `phpMyAdmin` or `mysql` to create DB and import `db/schema.sql`.
4. Update database config in `config.php`:
```php
<?php
$db_host = 'localhost';
$db_name = 'voting_db';
$db_user = 'root';
$db_pass = '';
?>
