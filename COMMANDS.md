## Docker Commands
---

<details close>

<summary><code> $ docker run nginx</code></summary>
<br>
The command "docker run nginx" is used to run a Docker container with the Nginx web server.

Here's what happens when you execute this command:

If you don't have the Nginx Docker image locally, Docker will download it from Docker Hub, which is the default public registry for Docker images.

Docker will then start a container based on the Nginx image, using the default settings. This will launch the Nginx web server and expose it on port 80.

Once the container is running, you can access the Nginx web server by opening a web browser and navigating to http://localhost.

If you want to stop the container, you can press Ctrl+C in the terminal or execute the "docker stop" command followed by the container ID or name. For example, "docker stop my-nginx-container".
</details>

<details close>

<summary><code> $ docker ps</code></summary>
<br>
The docker ps command is used to list all the running containers on a Docker host. It provides information such as the container ID, image used to create the container, command being run in the container, container status, ports being exposed, and the name of the container.
</details>
<details close>

<summary><code> $ docker ps -a</code></summary>
<br>
The docker ps -a command is used to list all the containers on a Docker host, including running and stopped containers. It provides similar information to docker ps, such as container ID, image used to create the container, command being run in the container, container status, ports being exposed, and the name of the container.
</details>
<details close>

<summary><code> $ docker stop [container id/name] </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $ docker rm [container id/name]</code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $ docker rmi [image id/name]</code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $ docker pull [image name]</code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $ docker run busybox sleep 10  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $ docker exec [container name/id] cat /etc/hosts  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $ docker run -d [image name/id]  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $ docker attach [container name/id]  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $ docker run -it [image id/name] /bin/bash  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $ docker kill $(docker ps -q) </code></summary>
<br>
The command docker kill $(docker ps -q) is used to kill all running Docker containers on the host.

Here's how the command works:

docker ps -q lists the IDs of all running containers on the Docker host.
$(docker ps -q) executes the docker ps -q command and returns a list of container IDs.
docker kill is used to send a SIGKILL signal to each container in the list of running containers returned by $(docker ps -q).
The docker kill command is a more forceful way of stopping a container than the docker stop command. It immediately sends a SIGKILL signal to the container, causing all processes running inside it to be abruptly terminated. Any changes made to the container's file system that are not committed to a new image or a data volume will be lost.

It's worth noting that using docker kill instead of docker stop should be used as a last resort, as it doesn't give the container a chance to shut down gracefully. However, in some cases, such as when a container is unresponsive or stuck in a loop, it may be necessary to use docker kill to stop it.
</details>

<details close>

<summary><code> $ docker rm $(docker ps -a -q) </code></summary>
<br>
Remove all containers
</details>

<details close>

<summary><code> $ docker run --name [container name] [image id/name] </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $ docker rmi $(docker rm -q) </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>

<details close>

<summary><code> $  </code></summary>
<br>
Well, you asked for it!
</details>