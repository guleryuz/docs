# Docker Images Available
Rocket.Chat is a rapidly-moving FOSS project. We maintain THREE Docker images for the diverse needs of our global users community. To use these images you will need to have [Docker] (https://docs.docker.com/engine/installation/) installed and operational.

Discovering existing releases: You can select the release you need from our [GitHub Release Page] (https://github.com/RocketChat/Rocket.Chat/releases). Here's a description of our [current branching strategy] (https://github.com/RocketChat/Rocket.Chat/wiki/Branches-and-Releases).  

### Official image (stable and tested)
The [Official Docker Images Repository] (https://docs.docker.com/docker-hub/official_repos/) is where Rocket.Chat's Official, stable image is maintained and controlled by Docker, and reviewed by the Docker committee.  
    
`docker pull rocket.chat`  
  
### Latest Release Image
This is an image that is maintained at Rocket.Chat's own docker repository. The release may be from the develop or master branch.
  
`docker pull rocketchat/rocket.chat:latest`  
  
### Specific Release Image  
This is an image that is maintained at Rocket.Chat's own docker repository. It is associated with a release build.

`docker pull rocketchat/rocket.chat:vX.X.X`