FROM ubuntu:latest

# Set working directory in the image
WORKDIR /app


# Copy files from host file system to image file system
COPY . /app


# Install necessary packages
RUN apt-get update && apt-get install -y python3 python3-pip

# Set environment variables
ENV NAME World

# Run a command to start the application
CMD ["python3", "app.py"]


