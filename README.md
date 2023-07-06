## Overview of Docker chain

**Dockerfile**  --'builds' to a--> **Docker Image** --'run it' into a--> **Docker Container**

1. Already having a Dockerfile in the root directory.


2. `docker build -t <IMAGE_NAME> .` * `-t` is for a tagname.*


3. `docker run -dp 8080:80 <IMAGE_NAME>` 

