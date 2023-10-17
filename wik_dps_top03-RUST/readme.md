#TP 01 :

## How to start the project with the default Port

    - cargo run

The default Port will be : ```8080```

## If you want to change the Port 

    - PING_LISTEN_PORT=9090 cargo run

```9090``` is an exemple, you can choice the port between 1000 and 65536

## What is the project

The project is an simple route of an API in Rust on: ```localhost:8080/ping``` who return the header of the page





docker build -t my-rust-app .
docker rm --force $(docker ps -aq)    
docker run -p 8080:8080 -d my-rust-app


user : 

docker exec -it ed7ac5bbcbb4 sh