# Pull the base image from Docker Hub
FROM python:3.11-slim

# Set the Working Directory inside the container
WORKDIR /app

# Copy files from host to container
COPY . .

# Install the required packages
RUN pip install -r requirements.txt

# Command to run the application
CMD [ "python", "main.py" ]