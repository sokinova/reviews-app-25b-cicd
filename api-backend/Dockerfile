# use an official Python runtime as a base image
FROM python:3.9-slim-buster

# Set the working directory 
WORKDIR /app

# Copy current directory code to /app in container 
COPY . .

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 80
EXPOSE 80

# Run app.py whent the container launches
CMD ["python", "app.py"]