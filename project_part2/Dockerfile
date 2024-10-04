# Dockerfile for book_catalog microservice
# Base image with Python 3.8 installed
FROM python:3.8-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any required Python packages
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 5000 to allow external access
EXPOSE 5000

# Define the command to run the application
CMD ["python", "app.py"]
