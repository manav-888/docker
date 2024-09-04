# docker Key



1. **Docker login**

2.  **docker stop** 
   ```
   docker stop container_ID
   ```

3. **Docker Start**
   ```
   docker start container_ID
   ```

4. **Docker Pull**
   ```
   docker pull <image_name>
   ```

5. **Docker rm**
-f flag: remove the container forcefully.
-v flag: remove the volumes.
-l flag: remove the specific link mentioned.
   ```
   docker image rm -f <ImageID>
   ```
6. **docker rm** 


7. **Docker images**
   ```
   docker images
   ```
8. **Docker PS**
   ```
   docker ps
   ```
9. **Docker build**
   ```
   docker build -t dockerimagename .
   ```

10. **Docker run**
   ```
   docker run -d -p 5000:5000 <dockerimagename>
   ```
or best way to do 
   ```
   docker run -p 5000:5000 <dockerimagename>
   ```
   ```
   docker run --rm <dockerimagename>
   ```

11. **Docker rename**
   ```
    docker image rm -f  dockerimagename
    docker build -t username/dockerimagename .
   ```
12. **Docker push**
   ```
   docker push username/dockerimagename:latest
   ```
