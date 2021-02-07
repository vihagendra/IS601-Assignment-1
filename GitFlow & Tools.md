##What is GitFlow?

*Gitflow Workflow is a Git workflow that helps with continuous software development and implementing DevOps practices. It was first published and made popular by Vincent Driessen at nvie. The Gitflow Workflow defines a strict branching model designed around the project release. This provides a robust framework for managing larger projects.*

![git Workflow](https://wac-cdn.atlassian.com/dam/jcr:61ccc620-5249-4338-be66-94d563f2843c/05%20(2).svg?cdnVersion=1446)

**The overall flow of gitglow is:**
1. A develop branch is created from master.
2. A release branch is created from develop.
3. Feature branches are created from develop.
4. When a feature is complete, it is merged into the develop branch.
5. When the release is done, it is merged into develop and master.
6. If an issue in master is detached a hotflix branch is created from master.
7. Once the hotflix is complete it is merged to both develop and master.

[Click Here to watch tutorial](https://www.youtube.com/watch?v=gLWSJXBbJuE&t=441s)

## Docker
*Docker is a set of platform as a service (PaaS) products that use OS-level virtualization to deliver software in packages called containers.Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels. Because all of the containers share the services of a single operating system kernel, they use fewer resources than virtual machines.*

![Containers VS VM's](https://www.microcontrollertips.com/wp-content/uploads/2017/01/VM-Diagram-opener.jpg)

### Advantages of Docker 

* Portability:
Once you have tested your containerized application you can deploy it to any other system where Docker is running and you can be sure that your application will perform exactly as it did when you tested it.

* Performance:
Although virtual machines are an alternative to containers, the fact that containers do not contain an operating system (whereas virtual machines do) means that containers have much smaller footprints than virtual machines, are faster to create, and quicker to start.

* Agility:
The portability and performance benefits offered by containers can help you make your development process more agile and responsive. 

* Isolation:
A Docker container that contains one of your applications also includes the relevant versions of any supporting software that your application requires. If other Docker containers contain applications that require different versions of the same supporting software, that isn't a problem because the different Docker containers are totally independent of one other.

* Scalability:
You can quickly create new containers if demand for your applications requires them. When using multiple containers you can take advantage of a range of container management options. See the Docker documentation for more information on these options.
  

