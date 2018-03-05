# The Experiment Factory Builder

![docs/img/expfactory.png](docs/img/expfactory.png)

This repository is provided for courtesy of the user to find information about the
builder, and report issues. The expfactory builder is provided on 
[Docker Hub](https://hub.docker.com/r/vanessa/expfactory-builder/) and is pushed
to this repository upon a new release of [The Experiment Factory](https://www.github.com/expfactory/expfactory)
base software. As a courtesy to the user, here we provide the logic and build setup
for generating this builder container.

 - The build files for Docker (Dockerfile and startscript.sh) are provided with the [core software](https://github.com/expfactory/expfactory/tree/master/expfactory/templates/build/docker).
 - When a new release of the software is provisioned, the [deploy_docker.sh](https://github.com/expfactory/expfactory/blob/master/script/deploy_docker.sh) script builds corresponding images for the builders, and survey and experiment generation containers.
 - The images built and pushed to Docker Hub for use.

If you want to see the build steps for any of the builder containers, reference the files above. If you have an issue, please [ask it here](https://www.github.com/expfactory/expfactory-builder). If you need to see documentation or instruction on how to use the builder, see our [generate](https://expfactory.github.io/expfactory/generate) pages.
