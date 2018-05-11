thedeep.network [README.md](thedeep-network/README.md)
===========================

O.G. Author: [@DeepInThought](https://github.com/DeepInThought)

| Repo Type     | Repo Name            | build status                      |
| ------------- |:--------------------:| ---------------------------------:|
|  GitHub.com   | [thedeep-network]    | [![CircleCI][ci-master]][master]  |
| Docker Hub    | [dockerhub-thedeep-network] | 

Our Purpose
-------

Officaial GitHub and Docker Hub repository for thedeep.network.

Docker Installation
-------
* For a list of tags, see this [Docker Hub tags](https://hub.docker.com/r/deepinthought/thedeep-network/tags/) page.
* The [Dockerfile](https://hub.docker.com/r/deepinthought/thedeep-network/~/dockerfile/) for more clarity.    

Docker Pull Commands:

```Dockerfile
$ docker pull deepinthought/thedeep-network
```

_Optional:_ If you want to pull a specific image [tag](https://hub.docker.com/r/deepinthought/thedeep-network/tags/).  i.e. deepinthought/thedeep-network:latest

```Dockerfile
$ docker pull deepinthought/thedeep-network:[TAG] for more options.
```

Docker Run Commands:

```Dockerfile
$ docker run --rm -it deepinthought/thedeep-network
```
        
_Optional:_ If you want to define the port configuration at run. 

```Dockerfile
$ docker run --rm -it -p 80:80 deepinthought/thedeep-network
```

About DeepInThought
-------
[@DeepInThought](https://github.com/DeepInThought) is a [St. Louis, Missouri](https://en.wikipedia.org/wiki/St._Louis) tech startup.  
* Official website is in development.
* Feel free to contact me at [support@deepinthought.io](mailto:support@deepinthought.io).  

![DeepIT](https://raw.githubusercontent.com/DeepInThought/deep-www/master/docs/images/deep_main.png)

[docs]: https://docs.thedeep.network
[thedeep-network]: https://github.com/DeepInThought/thedeep-network.git 
[dockerhub-thedeep-network]: https://hub.docker.com/r/deepinthought/thedeep-network/


[ci-master]: https://circleci.com/gh/DeepInThought/thedeep-network.svg?style=svg
[master]: https://circleci.com/gh/DeepInThought/thedeep-network/tree/master

