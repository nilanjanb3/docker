# *Top Docker Commands*

---

```sh
$ docker run nginx
```
The command "docker run nginx" is used to run a Docker container with the Nginx web server.

Here's what happens when you execute this command:

If you don't have the Nginx Docker image locally, Docker will download it from Docker Hub, which is the default public registry for Docker images.

Docker will then start a container based on the Nginx image, using the default settings. This will launch the Nginx web server and expose it on port 80.

Once the container is running, you can access the Nginx web server by opening a web browser and navigating to <http://localhost>.

If you want to stop the container, you can press Ctrl+C in the terminal or execute the "docker stop" command followed by the container ID or name. For example, "docker stop my-nginx-container".
<details close>

<summary><code> $ docker run nginx</code></summary>
<br>
The command "docker run nginx" is used to run a Docker container with the Nginx web server.

Here's what happens when you execute this command:

If you don't have the Nginx Docker image locally, Docker will download it from Docker Hub, which is the default public registry for Docker images.

Docker will then start a container based on the Nginx image, using the default settings. This will launch the Nginx web server and expose it on port 80.

Once the container is running, you can access the Nginx web server by opening a web browser and navigating to <http://localhost>.

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



| Commands | Description |
| :------| :-----------|
| `$ docker run nginx`   | If you don't have the Nginx Docker image locally, Docker will download it from Docker Hub, which is the default public registry for Docker images. Docker will then start a container based on the Nginx image, using the default settings. This will launch the Nginx web server and expose it on port 80. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |