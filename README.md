# Dockerize Google guetzli

Guetzli is a JPEG encoder, more infomation at https://github.com/google/guetzli .

## How to use

```shell
docker pull shawnoy/guetzli
docker run --rm -v $(pwd):/home/guetzli shawnoy/guetzli origin.jpg output.jpg
```
