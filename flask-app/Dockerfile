# Specify our base image
FROM python:3

# Set the working dir for our app
WORKDIR /usr/src/app

# Copy our application into the working dir
COPY . .

# Install the dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Open any ports that need to be exposed, our app is running on 5000
EXPOSE 5000

# Start the application
CMD [ "python", "./app.py" ]