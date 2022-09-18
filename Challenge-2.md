
# Create an Image Using a Dockerfile

Use a Dockerfile to create an image on the Docker host named myapp with tag 0.0.1.

Use the busybox image with tag 1.31.1 as the starting point for the image. 

Configure the image to use the nc -lv -p 5000 as the default command (This command uses netcat to listen for incoming TCP connections on port 5000). 

Ensure that containers created from the image will listen on port 5000.