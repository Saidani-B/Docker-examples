# hello world python project
this docker project builds a container based on the Ubuntu laest image. It starts by updating the Ubuntu system, then copies your Python script into the container, install Python 3 and Pip and sets an environment variable. when the container runs it executes the Python script, which prints "Hello World!"
# How it works:
1-To get started first make sure you have docer installed in your machine or follow this link "https://docs.docker.com/get-started/get-docker/"
2-clone the repo using "git clone" command
3-next build your image using: "docker build -t <image_name> .". make sure you are inside the FirstDockerFile folder 
4-run your application by: "docker run -d <image_name>"
5-you'll see "Hello World!" message in your terminal
