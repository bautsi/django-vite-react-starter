# Use an official Python runtime as the base image
FROM python:3.12

# Set the working directory inside the container
WORKDIR /app

# Copy requirements.txt into the container
COPY requirements.txt .

# Install the Python dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the rest of the backend code into the container
COPY . .

# Expose port 8000 for Django
EXPOSE 8000

# Command to run the Django development server
WORKDIR /app/asset_allocator
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
