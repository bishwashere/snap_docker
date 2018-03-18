# Create a file. Here Dockerfile and place the commands you want to run.
sudo docker build -t hello-world .

# Run your local docker image container.
sudo docker run -t hello-world

# If you run an image not locally available, docker will look for that image in docker-hub automatically, locate tge image if availabke, and downliad and run it.
sudo docker run -t alpine hostname
