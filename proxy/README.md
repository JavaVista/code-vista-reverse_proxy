## Docker

To build your Docker image:

```shell
docker build -t <name-of-your-image>:<version> .
```

To create a image

```shell
docker run -d --name <name-of-your-container> -p 80:80 <name-of-your-image>:<version>
```
