# What is gominer?

gominer is the console miner provided by [robvanmieghem](https://github.com/robvanmieghem/gominer).

gominer supports Siacoin (SC).

# How to use this image [AMD version]

Run in background:

```console
$ docker run -d --device /dev/dri:/dev/dri --name YOUR_CONTAINER_NAME calvintam236/gominer:amd -url YOUR_POOL_ADDRESS -user YOUR_USERNAME.YOUR_WORKER_NAME
```

Get `gominer` options with:

```console
$ docker run --rm calvintam236/gominer:amd -help
```

Fetch logs of a container:

```console
$ docker logs YOUR_CONTAINER_NAME
```
