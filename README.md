# User Authentication System with Fingerprint Integration

This project implements a user authentication system with traditional login (using email/password) and fingerprint authentication functionalities. Users can sign up by providing basic details like name, email, and password along with capturing their fingerprint data. Fingerprint data is securely stored and validated during login.

## Features

- User registration with basic details (name, email, password) and fingerprint data capture.
- Secure storage of user fingerprint data.
- User authentication using either email/password combination or fingerprint.
- Option for users to choose between traditional login and fingerprint authentication.
- Error handling and validation for data integrity and security.
- Clean and user-friendly interface for registration and login forms.

## Technologies Used

- Laravel framework for backend development.
- Laravel Breeze for streamlined authentication scaffolding.
- WebAuthn for integrating fingerprint authentication.
- [Add other relevant technologies here]

## Setup Instructions

1. Clone the repository:

```
git clone https://github.com/AbdulrahmanDaud10/laravel-fingerprint-authentication.git
```

2. Install dependencies:

```
composer install
```

3. Copy `.env.example` to `.env` and configure your database settings.
````
DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=fingerprint_auth
DB_USERNAME=yourusername
DB_PASSWORD=password
````

4. Generate application key:

```
php artisan key:generate
```

5. Migrate and seed the database:

```
php artisan migrate --seed
```

6. Run the development server:

```
php artisan serve
```

7. Visit `http://localhost:8000` in your browser to access the application.

## Usage

- Navigate to the registration page to sign up and provide your basic details along with fingerprint data.
- Once registered, you can log in using either your email/password combination or fingerprint.
- Choose the desired authentication method on the login page.

## Additional Notes

- Laravel Breeze provides a minimalistic authentication scaffold for rapid development.
- WebAuthn is utilized for integrating fingerprint authentication securely.

## Contributors

- [Abdulrahman Daud Miraj](https://github.com/AbdulrahmanDaud10)
 