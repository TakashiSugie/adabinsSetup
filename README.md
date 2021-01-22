first setup

docker pull zokashi/adabins

docker run -i -t --rm --gpus all -v [dirpath]:/wrk zokashi/adabins:latest /bin/bash
