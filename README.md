# docker-freeradius
Docker container with freeradius installation(based on ubuntu precise)

#### building the image
inside this repo run the following:
sudo docker build -t docker-freeradius -f Dockerfile .

#### running the container and exposing auth port (1812/udp)
sudo docker run -ti -p 1812:1812/udp docker-freeradius
