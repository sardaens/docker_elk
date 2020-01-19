# docker_elk
- To push container log into elk stack :
docker run -d -p 8080:80 --log-driver gelf --log-opt gelf-address=udp://localhost:12201 nginx:latest
