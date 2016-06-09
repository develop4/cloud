# cloud-config-files
Develop4 Spring Cloud Configuration Files


mvn clean package docker:build
docker run -p 8888:8888 --rm --name configserver develop4/configserver
