### The testing process
```
docker build -t no_flood_with_ai .
docker run --volume $(pwd)/datasets:/usr/src/app/datasets no_flood_with_ai 2020-10-11 2020-10-21
```
Note, you don't need to include datasets in a docker image.

As you can see, docker container runs with command line parameters that specifies the start and end of the period of data forecasts.
