# Pull the base image from php docker Hub
FROM php:8.4.18RC1-fpm-trixie

# Set the working directory inside the container
WORKDIR /app

# Copy files from host to container
COPY main.php .

# Command to run the application
CMD [ "php", "main.php" ]