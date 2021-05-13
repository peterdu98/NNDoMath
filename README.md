# Nerual network doing Math

This repository contains the implementation of neural network that is used for doing math.

## Description

Given a sequence of numbers, the trained neural network will predict the summation of them.

## Settings

Please download Docker Desktop before running the command below.

```shell
docker run -it --name nndomath -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD":/home/jovyan/work jupyter/datascience-notebook
```

If you have created the container but you turned it off before, please run the following command to start it.

```shell
docker start nndomath
```

Then, you need to open your browser with the URL of `localhost:8888`. Here, you will be asked for the token which can be found in your terminal.

> Note: If you could not find the token in your terminal, you can inspect logs of the container in Docker Desktop.

## Notes
1. Any changes made in the Docker container will be saved locally. Thus, please make sure everything before committing the code remotely.