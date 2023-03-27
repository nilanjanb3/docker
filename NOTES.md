# Docker Notes

---

### What is Containerization ?

Containerization is a technology that allows applications and their dependencies to be packaged into self-contained units called containers. Each container provides a lightweight and isolated runtime environment that includes everything needed to run the application, such as the application code, libraries, and system tools.

Containers use operating system-level virtualization to provide this isolation, which allows multiple containers to run on the same host system without interfering with each other. This approach differs from traditional virtualization, where each virtual machine runs a separate copy of the operating system and consumes more resources.

Containerization provides several benefits over traditional approaches to application deployment. First, it simplifies the process of deploying and running applications, as all the required dependencies are packaged together in a single container image. This can save time and reduce the risk of configuration errors.

Second, containers are highly portable, as they can be easily moved between different environments, such as development, testing, and production, without modification. This can simplify the process of deploying applications across multiple platforms.

Finally, containers offer increased scalability and resource utilization, as they can be easily deployed and managed in a distributed environment, such as a cloud-based infrastructure. This can help organizations to better optimize their resources and reduce costs.

### What is Docker ?

Docker is a popular platform used for developing, shipping, and running applications in a containerized environment. It allows developers to package their applications and dependencies into containers, which are self-contained and isolated from the host system and other containers.

Docker uses a client-server architecture, where the Docker client communicates with the Docker daemon, which is responsible for building, running, and managing containers. The Docker client and daemon can run on the same machine or on different machines, and communicate using REST API calls.

Docker containers are based on Docker images, which are essentially snapshots of an application and its dependencies at a given point in time. Docker images can be built manually or automatically using Dockerfiles, which are scripts that specify the steps needed to build an image.

With Docker, developers can easily create, deploy, and scale their applications across different environments, including on-premise servers, public clouds, and hybrid cloud environments. Docker also offers a rich ecosystem of tools and services, including Docker Compose, Docker Swarm, and Kubernetes, that can be used to orchestrate and manage containers at scale.

> Docker is based on **LCX** containerization technology

## Virtualization vs Docker

![](https://res.cloudinary.com/practicaldev/image/fetch/s--VoR6BpdY--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/o8gzz4378a6uokadhmsg.png)

## Advantages of Docker

- Caching a cluster of containers
- Flexible resource sharing
- Scalability - many containers can be placed in a single host
- Running your service on hardware that is much cheaper than standard servers
- Fast deployment, ease of creating new instances, and faster migrations.
- Ease of moving and maintaining your applications
- Better security, less access needed to work with the code running - - - inside containers, and fewer software dependencies

# h1

## h2

### h3

#### h4
