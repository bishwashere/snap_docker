# Create a file. Here Dockerfile and place
# commands you want to run.
sudo docker build -t hello-world .

# Run your local docker image in a container 
# named 'hello-world'.
sudo docker run -t hello-world

# If you run an image not locally available.
# Meaning you did not build it, docker will
# automatically look for that image in docker
# hub, download it and run it.
sudo docker run -t alpine hostname
