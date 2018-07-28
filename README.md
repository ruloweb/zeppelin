# Apache Zeppelin

An [Apache Zeppelin](https://zeppelin.apache.org/) container image, based on the [official image](https://store.docker.com/community/images/apache/zeppelin).

Python 3 is the default pyhton interpreter.

Packages installed:
* Scikit Learn
* Numpy,
* Pandas
* Scipy.

# Run

Using docker-compose:
```sh
docker-compose up
```

Or you can run:
```sh
docker run -it -v /notebook -e ZEPPELIN_NOTEBOOK_DIR=/notebook -p 8080:8080 --name zeppelin ruloweb/zeppelin:0.8.0
```
