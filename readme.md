This is a beginner Docker project.
It includes a Dockerfile that runs a lightweight Alpine container and prints a hello message.
EOF


Given commands 
first connected to VM 
sudo apt install docker.io
sudo usermod -aG docker ubuntu
then restart
docker run hello-world

docker build -t hello world -local:1.0

docker run --rm hello-world-local:1.0
output: Hello, World from Docker!

remeber in docker file created do not add EOF at last
