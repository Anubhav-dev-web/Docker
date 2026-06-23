# Pull base image for python
FROM python:3.8-slim

#Set the working directory in the Image
WORKDIR /app

# Copy the current directory contents into the container at /app in the image
COPY . /app 

# Run the application
CMD ["python", "app.py"] 