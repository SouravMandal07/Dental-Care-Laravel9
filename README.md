# Portfolio website
https://codersourav.000webhostapp.com


# Dental Clinic Template
<p>Template for a dental clinic created with <a href="https://tallstack.dev/" target="_blank">TALL</a> stack, with appointment booking feature and admin panel to manage appointments.

## Installation
Clone the repository, navigate to project directory and install dependencies
```bash
composer install
```
  
Create a file for environment variables by coping `.env.example`
```bash
cp .env.example .env
```

Create application key
```bash
php artisan key:generate
```

Setup database credentials in `.env` file and run migrations
```bash
php artisan migrate
```

To seed the database with some test data run
```bash
php artisan db:seed

# Run project
php artisan serve


## Usage
When you seed your database, there will be account created for testing
  
```
Email: testuser@example.com
Password: password
```
To be able to send email from contact form you should have configured SMTP server and you should have configured email address in .env
```
CONTACT_FORM_TO="testuser@example.com"
```
## Testing
```bash
php artisan test
```
## Screenshots
![dental-1](https://github.com/SouravMandal07/Dental-Care-Laravel9/assets/86459723/d0187428-feed-48cc-8ecd-19a3aadeeff1)
![dental-2](https://github.com/SouravMandal07/Dental-Care-Laravel9/assets/86459723/61038c88-d165-4374-b319-ca16bab1e15c)
![dental-3](https://github.com/SouravMandal07/Dental-Care-Laravel9/assets/86459723/a20982b3-1d41-4906-8368-10bfd35b1401)
![dental-4](https://github.com/SouravMandal07/Dental-Care-Laravel9/assets/86459723/102a6270-884a-415e-a51b-e349621bd066)
![dental-5](https://github.com/SouravMandal07/Dental-Care-Laravel9/assets/86459723/e6520045-2f4d-4451-8f72-78c8a12766bd)
![dental-6](https://github.com/SouravMandal07/Dental-Care-Laravel9/assets/86459723/ecc83ab1-b11c-4ff9-be42-ce8173efadce)
![dental-7](https://github.com/SouravMandal07/Dental-Care-Laravel9/assets/86459723/20a6caa8-3c0b-4259-a6cf-09570f383bba)
![dental-8](https://github.com/SouravMandal07/Dental-Care-Laravel9/assets/86459723/4a0350d7-583e-4365-85e1-26783b1a0add)
![dental-9](https://github.com/SouravMandal07/Dental-Care-Laravel9/assets/86459723/e25de822-142e-4ca3-970d-55c8fad542b1)

