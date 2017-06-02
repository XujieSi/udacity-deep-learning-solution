# udacity-deep-learning-solution
Tentative Solution for Udacity Deep Learning course taught by Vincent Vanhoucke


Docker Related Commands:

```
# start docker
docker start -ai tensorflow-udacity

# stop docker
docker stop tensorflow-udacity

# update environment 
eval $(docker-machine env devbox)

# run bash in docker virtual machine
docker  exec -i -t tensorflow-udacity /bin/bash

# list docker running machines
docker ps

# check virtual machine ip
docker-machine ip devbox

# check docker log
docker container logs tensorflow-udacity
```


