# connectors
Final Group Project Submission for CS34 - Web Technologies course at Ashesi University. Group members were:
- Ademide Mubarak Adebanjo
- Cindy Wanyika Kilonzo
- Zeinab Amadou Hamidou
- Josephine Forgive Doamekpor
  
## Features

- User authentication (signup/login)
- Connections with other users
- Messaging functionality
- Secure password hashing
- Access Control

## Requirements

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web server (Apache/Nginx)
- Modern web browser

## Setup
1. *Prerequisites*
   - Install XAMPP
   - Enable PHP PDO MySQL extension

2. *Database Setup*
   - Create a new MySQL database: webtech_2025A_zeinab_hamidou 
   - Import the database schema from setup/databaseSetup.sql
   - (Optional) Import sample data from setup/sampleData.sql

3. *Configuration*
   - Update database credentials in config/database.php if needed
   - Default credentials (for XAMPP):
     - Username: root
     - Password: `` (empty)
     - Database: webtech_2025A_zeinab_hamidou

4. *Running the Application*
   - Place the project in your web server's root directory (e.g., htdocs/connectors)
   - Start your local web server and MySQL server
   - Access the application at: http://localhost/connectors/landing_page.html

## Folder Structure

- /config - Database configuration
- /assets - Image assets
- /setup - Database schema and sample data
- Root directory - Main application files and entry points

## Troubleshooting

- *Database Connection Issues*
  - Verify database credentials in config/database.php
  - Ensure MySQL server is running
  - Check if the database and tables exist

- *Permission Issues*
  - Ensure web server has read access to all files
  - Check write permissions for file uploads if implemented

- *Page Not Found*
  - Check if URL rewriting is properly configured
  - Ensure .htaccess is being processed (if using Apache)

## Support

For assistance, please contact any of the group members.
