
# Use the official Python image
FROM python:3.9

# Set the working directory
WORKDIR /app

# Copy the current directory contents into the container
COPY . .

# Install dependencies
RUN pip install flask

# Expose the port the app runs on
EXPOSE 5000

# Run the application
CMD ["python", "app/app.py"]
