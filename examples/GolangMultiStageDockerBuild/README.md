# Go Multi-stage Calculator
# How it works
This project builds a small Go application using a multi stage Docker build. First it uses a Golang image to turn your source code into a runnable file. Then it creates a final tiny image based on scratch and copies just that binary over which makes the resulting image really small 
