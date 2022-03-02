# My Docker Xampp

## Description
Docker Xampp with PHP, Apache, Mariadb and phpMyAdmin to work with MVC projects, Twig and Doctrine.

### Database
Put the .sql file in the dump directory to insert into the container.
- Default database user: `root`
- Default database password: `root`

### Generate vendor
To generate the vendor folder you will need to have composer installed and inside the www/ directory run the command: `composer install` 

### Generate src/
Inside the www/ directory generate a folder src/ and add to this controllers, entity, repositories and core.

### Run the container
To run the container use:
    `docker-compose up --build`

### Access
Access to the application:
    http://localhost:80

Access to phpMyAdmin:
    http://localhost:8080