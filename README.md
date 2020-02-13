# udacity-capstone

This is a project for udacity nanodegree Cloud dev-ops Engineer about to deploy a web app using a docker image and jenkins to run a pipeline.


## The files included are:
```sh
* ./Dockerfile : Dockerfile for building the image with nginx server
* Jenkinsfile : to deploy the insfrastructure into amazon AWS using EKS.
* ./index.html : The web application to deploy.
* ./blue-controller.json: The controller to deploy blue proecess
* ./gree-controller.json: The controller to deploy green process
* ./Jenkinsfile : the file to deploy all the CI/CD process into EKS cluster.


License
-------
udacity-IaC is a public domain work, dedicated using
[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Feel free to do
whatever you want with it.
