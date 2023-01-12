This instructions are for build and push on dockerhub.

First have be logged on Docker Hub
```sh
docker login
```

Build image
```sh
cd php-[tagname]
docker build -t pablo262/php:[tagname] .
```

Push imagen on Docker Hub
```sh
docker push pablo262/php:[tagname]
```
