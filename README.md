# Node.js micro-services template for Platform.sh

This project provides a starter kit for Node.js projects hosted on Platform.sh. It is primarily an example, although could be used as the starting point for a real project.

In this example we are going to launch 9 different micro-services. One of the applications (app1) is configured through its relationship key to be able to connect to the other 8.

> note that currently this (9 app services + a database) is the upper limit on the Large plan of platform.sh, you will need to contact
> sales to get a bigger platform.


There is also a mongodb instance running in the cluster to which all of the apps can connect.

## Starting a new project

To start a new project based on this template, follow these 3 simple steps:

1. Clone this repository locally.  You may optionally remove the `origin` remote or remove the `.git` directory and re-init the project if you want a clean history.
 
2. Create a new project through the Platform.sh user interface and select "Import an existing project" when prompted.

3. Run the provided Git commands to add a Platform.sh remote and push the code to the Platform.sh repository.

That's it!  You now have a working "hello world" level project you can build on.

## Using as a reference

You can also use this repository as a reference for your own projects, and borrow whatever code is needed. The most important parts are the `.platform.app.yaml` file and the `.platform` directory.
