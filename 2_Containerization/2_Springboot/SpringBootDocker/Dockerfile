FROM openjdk:17

COPY ./target/Demo.jar .

WORKDIR .

#When we run this application it runs within the container on port 8080.
# Any port within the container is not accessible to outside world unless published explicitly
# In other words you have to bind host machine port with container port

EXPOSE 8080

CMD [ "java","-jar","Demo.jar" ]