# docker-fio
fio is IO benchmark docker image with fio cli

## how to run the benchmark

To test the performance of the storage, just go in a folder that mounts the storage and run : 
```bash
docker run -it --rm -v $PWD:/data ghcr.io/j3k4/docker-fio
```

You will get the benchmark result in container output
