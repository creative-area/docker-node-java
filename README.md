# Docker Node + Java

This image extends the official Node image and add supports for Java.

This is a base image for development purpose.

## Usage example

```
docker run -ti -p 80:80 -v $(pwd):/usr/src/app creativearea/node-java bash
```
