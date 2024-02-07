VERY short example code to create a Web app with Flask, create a Docker image and a Docker container of it.

The Dockerfile uses a Python 3.9 image, sets the WORKDIR inside the image on '/app' and copies the entire content on it. Also, runs the 'pip install' command to install Flask that's in the requirements file. Finally, runs the web app.

To create the Docker image, run the next command in the app directory: 
docker build -t my_app .

To create the Docker container, using the recently created image, run the command: 
docker build -t my_app .
