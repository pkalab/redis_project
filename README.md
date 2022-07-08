# Test Project

Node , redis , docker simple to do list

# How to use

```
git clone https://github.com/pkalab/redis_project.git
cd redis_project
docker-compose up --build
```

open http://localhost:9001/

# To bring docker down use

```
docker-compose down
```

Before accessing docker containers run docker-compose down

# To access redis database

```
 cd redis_project
 docker run -d --name redis -p 127.0.0.1:${HOST_MACHINE_REDIS_PORT}:6379 redis
 docker exec -it redis sh
```
