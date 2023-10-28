To run this container first build a image with
`docker build -t demo-volume .`

Then we build a volume to use
`docker volume create volume1`

Then we run the container
`docker run -d -p 8080:80 -v volume1:/usr/share/nginx/html demo-volume`


>In windows we can find the volume in `\\wsl$\docker-desktop-data\data\docker\volumes`