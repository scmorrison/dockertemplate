# Docker template 

This is a simple template for building out a Debian container based off of the "semi-official" debian images.

## Build the container using:

```
sudo docker build -t="smorrison/stockdeb:v1" .
```

## Run the image in a new container:

```
./runimage.sh
```

## Connect to new container

```
ssh root@0.0.0.0 -p2222
```

root password: root

## The container 
