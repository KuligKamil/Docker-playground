docker run -p 27017:27017 --network="bridge" --name some-mongo -v /test/mongo/data:/data/db -d mongo
docker run -it --network="bridge" --name light-python python:3.7-slim /bin/bash

