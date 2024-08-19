# app-config-server
spring config server

# docker build
docker build -t mady-consulting/config-server:0.0.1 .

# docker run command 
docker run -d -p 8080:8888 --name testConfig mady-consulting/config-server:0.0.1