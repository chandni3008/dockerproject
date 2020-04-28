Docker is an open source platform that helps you build, run and deploy applications. It is a containerization tool that allows you to set up separate “containers” which include a complete development environment. These individual containers are similar to virtual machines, but they don’t require you to install a complete operating system to be able to run them.
Since these containers are usually more lightweight than a virtual machine, you can easily setup multiple containers without slowing down your computer. What’s more, each of these containers uses a configuration file which makes it easy to transfer the container to a different machine or upload it to the cloud. You can use Docker to create a development environment for any type of application. Docker is an open-source application and can be installed on Windows, Linux, and Mac computers.
Benefits of Using Docker:
No Need to Set Up (Multiple) Server Environments.
Less Resource Heavy Than a Virtual Machine.
Can Be Used on Any Platform.
Docker is cross-platform compatible.
Allows Collaboration on Containers.
Containers are isolated from each other.

In this project I have installed WordPress with mysql (for backend) using docker. Docker will run WordPress in an isolated environment.
This project directory contains a docker-compose.yml file which is complete in itself for wordpress project as it contains WordPress, and a separate MySQL instance with a volume mount for data persistence.
We can create environment according to our need and it can be launched within a small amount of time without waiting for long like the traditional methods. 
