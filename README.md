# Pet Management System

A web-based pet management system built with PHP that allows users to manage pet-related services and reservations.

## Features

- User authentication system (login/register)
- Pet reservation management
- Admin dashboard for managing reservations and users
- Contact management
- Available services listing
- Message management

## Project Structure

```
pet/
├── about-us.php         # About page
├── addcnp.php           # Add new pet service
├── admin_reject_completed.php # Admin reject completed reservations
├── admin_reservefilter.php  # Admin reservation filtering
├── adminacc.php         # Admin account management
├── adminacc_process.php # Admin account processing
├── adminlogin_process.php # Admin login processing
├── available.php        # Available services listing
├── availableframe.php   # Available services frame
├── contacts.php         # Contact management
├── css/                 # CSS stylesheets
├── database/           # Database files
├── deleteModal.php     # Delete modal functionality
├── deletemessage_process.php # Delete message processing
├── deletemodalprocess.php # Delete modal processing
├── fonts/              # Font files
├── images/             # Image assets
├── includes/           # Include files
├── index.php           # Main entry point
├── js/                 # JavaScript files
├── loginModal.php      # Login modal functionality
├── logout_process.php  # Logout processing
├── updateModal.php     # Update modal functionality
├── update_cnp.php      # Update pet service
└── updatefbw_process.php # Feedback processing
```

## Requirements

- PHP 7.0 or higher
- MySQL database
- Web server (Apache/Nginx)
- Modern web browser

## Installation

1. Clone the repository to your web server directory
2. Import the database schema from the `database` folder
3. Configure your web server to point to the project root directory
4. Ensure PHP and MySQL are properly configured
5. Access the application through your web browser

## Usage

1. Visit the main page (`index.php`)
2. Login using admin credentials or register a new account
3. Use the navigation menu to access different features
4. Manage pet services, reservations, and user accounts

## Security

The application includes basic security measures:
- Password hashing
- Input validation
- Session management
- SQL injection prevention

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is proprietary software. All rights reserved.

## Support

For support, please contact the project maintainer or check the documentation.
