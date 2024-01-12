---
description: >-
  Docker Extensions lets you use third-party tools within Docker Desktop to
  extend its functionality.
cover: .gitbook/assets/1_WiJWV1yO5gpmHV7Jw7Hvgw (1).png
coverY: 0
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 👋 A Curated List of Docker Extensions

<details>

<summary><mark style="color:green;"><strong>Why Developers Need Docker Extensions</strong></mark> </summary>

* Extensions allows developers to seamlessly connect their favourite development tools to your application development and deployment workflows

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

<summary><mark style="color:green;"><strong>Featured Docker Extension( Jan 2024)</strong></mark></summary>

* [MindsDB Docker Extensions](https://hub.docker.com/r/ajeetraina/mindsdb-docker-extension)
* [Livecycle Docker Extension](https://www.docker.com/blog/livecycle-doDr-extension/)
* [Warp Docker Extension](https://hub.docker.com/extensions/warpdotdev/warp)
* [Docker Labs K8s Toolkit](https://hub.docker.com/extensions/docker/labs-k8s-toolkit-extension)
* [Jmeter Docker Extension](https://qainsights.com/introducing-the-apache-jmeter-docker-extension/)
* [JupyterLab Docker Extension](https://www.docker.com/blog/getting-started-with-jupyterlab-as-a-docker-extension/)
* [Grafana Docker Extension](https://www.docker.com/blog/unlock-docker-desktop-real-time-insights-with-the-grafana-docker-extension/)
* [Memgraph Docker Extension](https://www.docker.com/blog/memgraph-docker-extension-empowering-real-time-analytics-with-high-performance/)
* [Docker Labs Debug Tools](https://hub.docker.com/extensions/docker/labs-debug-tools-extension)

</details>

<details>

<summary><a href="https://github.com/docker/extension-ideas/discussions">💡 Submit your Docker Extensions Ideas</a></summary>

Here's a place to suggest new ideas for Docker Extensions and get new ideas of what to build for the larger Docker community.

</details>

<details>

<summary><mark style="color:green;"><strong>How to install Docker Extensions?</strong></mark></summary>

Using GitHub

{% code title="Step 1. Clone the repository." %}
```bash
 git clone https://github.com/<repo-name>/<name-of-your-extension>
```
{% endcode %}

{% code title="Step 2. Build the Docker Extension Navigate into the cloned repository and run:" %}
```bash
 make build-extension
```
{% endcode %}

The above command generates a Docker image named after the Docker Hub repository.

To install the extension in Docker Desktop, run:

{% code title="Step 3. Install Docker Extensions" %}
```bash
 docker extension install <repo-name>/<name-of-your-extension>
```
{% endcode %}

You can also check that the extension has been installed successfully using the following CLI command:

{% code title="Step 4. List the Extension" %}
```bash
 docker extension ls
```
{% endcode %}

### Using Docker Hub

{% code title="Step 1. Pull the image" %}
```bash
 docker pull <Docker-Hub-username>/<image-name>
```
{% endcode %}

To install the extension in Docker Desktop, run:

{% code title="Step 2. Install Docker Extensions" %}
```bash
 docker extension install <Docker-Hub-username>/<image-name>
```
{% endcode %}

</details>
