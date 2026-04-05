# Python Web Application
This project sets up a Django web application using  a Dockerfile and DockerCompose. The Dockerfile starts from an Ubuntu bases installs Python 3 and dependencies, sets up a virtual environment, copies your code, and runs the Django development sever. The main folder contains the docker compose file while the app folder holds you actual python code. this makes it easy to manage the app and its database together
# How it works
1-First of all you need docker and docker compose installed. if they are not go to "https://docs.docker.com/get-started/get-docker/"

2-clone the repo using "git clone" command
```bash
git clone https://github.com/Saidani-B/Docker-examples.git
cd Docker-examples
cd PythonWebApp
```
3-once you done, build and run your app by using this command
```bash
docker-compose up --build
```
4-Finally you can check if the app is running. open your browser and go to localhost on post `8000`
