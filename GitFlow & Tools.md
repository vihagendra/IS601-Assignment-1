## What is GitFlow?

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
  
## Automated Testing & Continuous Integration
* **Automated testing** is the application of software tools to automate a human driven manual process of reviewing and validating a software product. Most modern software projects now include automated testing from inception. To fully appreciate the value of automated testing, however, it helps to understand what life was like  before it was widely adopted.
* **Continuous Integration** Continuous Integration (CI) is a development practice where developers integrate code into a shared repository frequently, preferably several times a day. Each integration can then be verified by an automated build and automated tests. While automated testing is not strictly part of CI it is typically implied.

## Why Automate Testing in CI 

* In recent years CI has become a best practice for software development and is guided by a set of key principles. Among them are revision control, build automation and automated testing.

* **"Continuous Integration does not get rid of bugs, but it does make them dramatically easier to find and remove"** 

* Agile teams iterate faster to deliver software and customer satisfaction at higher rates, and these pressures can jeopardize quality. Global competition has created low tolerance for defects while increasing pressure on agile teams for faster iterations of software delivery. What's the industry solution to alleviate this pressure? **DevOps.**

## Benefits of an Automated Continuous Development Process
There are five aspects of a continuous development process you’ll benefit from by transitioning to the CI/CD pipeline:

* Faster Release Cycles: Speeding up the build and deploy cycle will allow you and your team to get new features into production quicker, meaning you can get your product into the hands of your consumers faster.
* Reduced Risk: The ultimate goal of a continuous delivery process is to make each release a less-dramatic and painless experience for both the QA teams and customers. By releasing new updates or features continuously, you reduce the risk of bugs ending up in production and can resolve any found deficiencies faster.
* Lower Costs: Adopting a continuous development model will lower your costs by eliminating many of the fixed costs associated with building and testing changes to the application. For example, automated environment provisioning will reduce the costs associated with maintaining your own test infrastructure. Parallel testing will cut down on the number of machines you need to run your tests on. By continuously committing your code, you’ll spend less time (and therefore money) on fixing bugs.
* Higher Quality Products: A major fear of implementing the CI/CD pipeline is foregoing quality for speed, but this isn’t the case. Continuous integration enables stronger collaboration between developers, meaning bugs are found and fixed faster earlier in the development process. Running automated regression and parallel tests will improve test coverage, ensuring your application is bug-free and works across a wider range of environments. Continuously delivering smaller updates to your software will make most changes (and bugs) undetectable to the end user, resulting in happier customers.
* Better Business Advantage: Moving to a continuous development model gives your team the flexibility to make alterations to your software on-the-go to meet new market trends and user needs. You’ll be able to meet rapidly changing demands and will turn your release process into a competitive advantage.

[Changelog](Changelog.md)
