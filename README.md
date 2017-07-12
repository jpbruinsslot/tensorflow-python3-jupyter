**DEPRECATED**

Please use the official TensorFlow docker image:

* [Tensorflow](https://www.tensorflow.org/install/install_linux#InstallingDocker)
* [Github](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/tools/docker)

---

Tensorflow Python3 Jupyter
==========================

Docker container with python 3 version of tensorflow accompanied by jupyter

Usage
-----

```bash
$ docker run -p 8888:8888 \
    -v [path-to-notebooks]:/notebooks \
    -it erroneousboat/tensorflow-python3-jupyter
```
