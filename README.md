---
description: >-
  Docker Extensions lets you use third-party tools within Docker Desktop to
  extend its functionality.
cover: >-
  https://images.unsplash.com/photo-1528605248644-14dd04022da1?crop=entropy&cs=tinysrgb&fm=jpg&ixid=MnwxOTcwMjR8MHwxfHNlYXJjaHwxMHx8dGVhbSUyMG9mJTIwcGVvcGxlfGVufDB8fHx8MTY2MDMxNzQzNg&ixlib=rb-1.2.1&q=80
coverY: 0
---

# 👋 A Curated List of Docker Extensions

<details>

<summary>Why Developers Need Docker Extensions </summary>



* Extensions allows developers to seamlessly connect their favorite development tools to your application development and deployment workflows

<!---->

* Extensions augments Docker Desktop with debugging, testing, security, and networking functionalities, and build custom add-ons using the Extensions SDK

<!---->

* Extensions open a realm of possibilities for developers by adding a variety of tools to your development workflows

<!---->

* Developers can now leverage their favorite tools directly from within Docker Desktop with one-click installation of extensions

<!---->

* Developers can now discover new ways to implement and optimize workflows in the Marketplace with Extensions from both official Extension partners and community members



</details>

<details>

<summary>Featured Docker Extension( Jan 2024)</summary>

* [MindsDB Docker Extension](https://hub.docker.com/r/ajeetraina/mindsdb-docker-extension)
* [Livecycle Docker Extension](https://www.docker.com/blog/livecycle-doDr-extension/)
* [Warp Docker Extension](https://hub.docker.com/extensions/warpdotdev/warp)
* [Docker Labs K8s Toolkit](https://hub.docker.com/extensions/docker/labs-k8s-toolkit-extension)
* [Jmeter Docker Extension](https://qainsights.com/introducing-the-apache-jmeter-docker-extension/)
* [JupyterLab Docker Extension](https://www.docker.com/blog/getting-started-with-jupyterlab-as-a-docker-extension/)
* [Grafana Docker Extension](https://www.docker.com/blog/unlock-docker-desktop-real-time-insights-with-the-grafana-docker-extension/)
* [Memgraph Docker Extension](https://www.docker.com/blog/memgraph-docker-extension-empowering-real-time-analytics-with-high-performance/)
* [Docker Labs Debug Tools](https://hub.docker.com/extensions/docker/labs-debug-tools-extension)

###

\


</details>

<details>

<summary><a href="https://github.com/docker/extension-ideas/discussions">💡 Submit your Docker Extensions Ideas</a></summary>

Here's a place to suggest new ideas for Docker Extensions and get new ideas of what to build for the larger Docker community.

</details>

<details>

<summary>How to install Docker Extensions</summary>



### Using GitHub

#### Step 1. Clone the repository

```
 git clone https://github.com/<repo-name>/<name-of-your-extension>
```

#### Step 2. Build the Docker Extension

Navigate into the cloned repository and run:

```
 make build-extension
```

The above command generates a Docker image named after the Docker Hub repository.

#### Step 3. Install Docker Extensions

To install the extension in Docker Desktop, run:

```
 docker extension install <repo-name>/<name-of-your-extension>
```

#### Step 4. List the Extension

You can also check that the extension has been installed successfully using the following CLI command:

```
 docker extension ls
```

### Using Docker Hub

#### Step 1. Pull the image

```
 docker pull <Docker-Hub-username>/<image-name>
```

#### Step 2. Install Docker Extensions

To install the extension in Docker Desktop, run:

```
 docker extension install <Docker-Hub-username>/<image-name>
```

</details>
