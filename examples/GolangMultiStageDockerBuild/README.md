# Go Multi-stage Calculator
This project builds a small Go application using a multi stage Docker build. First it uses a Golang image to turn your source code into a runnable file. Then it creates a final tiny image based on scratch and copies just that binary over which makes the resulting image really small 
# How it works
1-First of all you need docker and docker compose installed. if they are not go to "https://docs.docker.com/get-started/get-docker/"
2-clone the project using "git clone" command
3-once you done, build and run your app by using this command: "docker-compose up --build".make sure you are in GolangMultiStageDockerBuild folder 
4-you check if the app is running by looking for its logs in the terminal
