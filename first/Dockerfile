FROM ubuntu:latest

# Set working directory in the image
WORKDIR /app

# Copy the file from the host file system
COPY . /app

# Install the necessary packages
RUN apt-get update && apt-get install -y python3 python3-pip

# Set environment variable
ENV NAME WORLD

# Run a command to start the application
CMD ["python3", "hello.py"]
