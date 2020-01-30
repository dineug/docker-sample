# Jupyter

```bash
$ docker run --gpus all --restart=always --name dineug-jupyter -p 8888:8888 -it -v /home/dineug/docker/volume/jupyter:/tf/notebooks tensorflow/tensorflow:2.0.0-gpu-py3-jupyter
```

## Reference
- https://hub.docker.com/r/tensorflow/tensorflow/
- https://github.com/NVIDIA/nvidia-docker
