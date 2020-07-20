# Use the python3.7.2 container image
FROM python:3.7.2-stretch

# Set up the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
ADD . /app

# Install the dependencies
RUN pip install -r requirements.txt

# run the commend to start uWSGI
CMD ["uwsgi", "app.ini"]
