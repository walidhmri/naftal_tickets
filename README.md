updated 27/03/2025 by oualid

## Features

*   [List key features of the website, e.g., Responsive design, Contact form, Blog section, etc.]
*   [Another feature]
*   [And another one]
*   [New Feature 1: Dark mode support]
*   [New Feature 2: Interactive animations]
*   [New Feature 3: Live chat support]

## Getting Started

## Docker with php,mysql,phpmyadmin
## Docker guide available on dockerguid.md
# Laravel Dockerized Project

## Overview

This project is a Laravel application containerized with Docker, using PHP 8.2, MySQL, and phpMyAdmin.

## Prerequisites

Ensure you have the following installed on your system:

- Docker & Docker Compose
- Git

## Setup Instructions

### 1. Clone the Repository

```sh
git clone https://github.com/walidhmri/dockerise.git
cd dockerise
```

### 2. Configure Environment Variables

Copy the example environment file and configure it if needed:

```sh
cp .env.example .env
```

Modify `.env` with your database credentials and application settings if you modified any of them.

### 3. Build and Start Containers
note: -d to run in background
```sh
docker-compose up --build -d 
```

This will start:

- Laravel application (PHP 8.2)
- MySQL database
- phpMyAdmin



### 4. Access the Application

- Laravel API/UI: [http://localhost:8000](http://localhost:8000)
- phpMyAdmin: [http://localhost:9000](http://localhost:9000) (Host: `mysql`, User: `root`, Password: `root`), (Host: `mysql`, User: `user`, Password: `password`)

### 5. Stop and Remove Containers

To stop containers:

```sh
docker-compose down
```

To remove all containers, networks, and volumes:

```sh
docker-compose down -v
```
## Connect to the secret santa with this credentials:

email: 
```
user@walidhmri.io
```
password
```
password
```

## Contributing

Feel free to fork the repository and submit pull requests.

## License

free to use.


## If you have any troubles feel free to contact me at : 

contact at :
```
 oualidhamri@icloud.com
```
or :
```
 oualid.hamri@univ-bouira.dz
 ```
 Enjoy

## Contact

If you have any questions or suggestions, feel free to reach out to me:

*   Name: Oualid Hamri
*   Email: [your email address]
*   [Link to your portfolio or social media]

## License

[Specify the license under which the code is released, e.g., MIT License, GPL, etc.]
