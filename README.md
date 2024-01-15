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

<summary><mark style="color:green;"><strong>Why Developers Need Docker Extensions</strong></mark></summary>

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

* [MindsDB Docker Extension](https://hub.docker.com/r/ajeetraina/mindsdb-docker-extension)
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

#### Using Docker Hub

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

### <mark style="color:yellow;">List of Docker Marketplace Extensions</mark>

Here is a list of Docker Extensions available in Docker Hub:

<table><thead><tr><th width="84">S.No.</th><th width="193">Name of Extensions</th><th width="201">Description</th><th width="145">Docker Desktop</th><th width="128">DockerHub</th><th>Popularity</th></tr></thead><tbody><tr><td>1</td><td>Disk Usage</td><td>View disk space used by Docker and reclaim space in one click</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=docker/disk-usage-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/docker/disk-usage-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/docker/disk-usage-extension" alt="Docker Pulls"></td></tr><tr><td>2</td><td>Logs Explorer</td><td>View all container logs in one place so you can debug and troubleshoot faster</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=docker/logs-explorer-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/docker/logs-explorer-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/docker/logs-explorer-extension" alt="Docker Pulls"></td></tr><tr><td>3</td><td>Resource Usage</td><td>Monitor and manage live data stream for running containers</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=docker/resource-usage-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/docker/resource-usage-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/docker/resource-usage-extension" alt="Docker Pulls"></td></tr><tr><td>4</td><td>Volumes Backup &#x26; Share</td><td>Backup, clone, restore, and share Docker volumes effortlessly</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=docker/volumes-backup-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/docker/volumes-backup-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/docker/volumes-backup-extension" alt="Docker Pulls"></td></tr><tr><td>5</td><td>Uffizzi</td><td>Uffizzi lets you create and manage full-stack previews in the cloud from Docker Compose</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=uffizzi/docker-desktop-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/uffizzi/docker-desktop-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/uffizzi/docker-desktop-extension" alt="Docker Pulls"></td></tr><tr><td>6</td><td>Portainer</td><td>Docker container management made simple, with the world’s most popular GUI-based container management platform</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=portainer/portainer-docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/portainer/portainer-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/portainer/portainer-docker-extension" alt="Docker Pulls"></td></tr><tr><td>7</td><td>Okteto</td><td>Remote Development for Docker Compose</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=okteto/docker-desktop-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/okteto/docker-desktop-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/okteto/docker-desktop-extension" alt="Docker Pulls"></td></tr><tr><td>8</td><td>Ambassador Telepresence</td><td>Instantly bridge your workstation with Kubernetes clusters in the cloud</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=ambassador/telepresence-docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/ambassador/telepresence-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/ambassador/telepresence-docker-extension" alt="Docker Pulls"></td></tr><tr><td>9</td><td>Snyk</td><td>Scan your remote or local image and detect any contained vulnerabilities</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=snyk/snyk-docker-desktop-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/snyk/snyk-docker-desktop-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/snyk/snyk-docker-desktop-extension" alt="Docker Pulls"></td></tr><tr><td>10</td><td>Slim.AI</td><td>Deep dive into the construction of your images. Know what's in your containers</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=slimdotai/dd-ext">Install</a></td><td><a href="https://hub.docker.com/extensions/slimdotai/dd-ext">Link</a></td><td><img src="https://img.shields.io/docker/pulls/slimdotai/dd-ext" alt="Docker Pulls"></td></tr><tr><td>11</td><td>Lacework Scanner</td><td>Minimize the vulnerabilities before the images go into production</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=lacework/lacework-docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/lacework/lacework-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/lacework/lacework-docker-extension" alt="Docker Pulls"></td></tr><tr><td>12</td><td>Anchore</td><td>Content and security analysis for container images</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=anchore/docker-desktop-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/anchore/docker-desktop-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/anchore/docker-desktop-extension" alt="Docker Pulls"></td></tr><tr><td>13</td><td>Calyptia Core</td><td>Use Calyptia Core within Docker Desktop to manage observability</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=calyptia/core-docker-desktop">Install</a></td><td><a href="https://hub.docker.com/extensions/calyptia/core-docker-desktop">Link</a></td><td><img src="https://img.shields.io/docker/pulls/calyptia/core-docker-desktop" alt="Docker Pulls"></td></tr><tr><td>14</td><td>InterSystems</td><td>Access InterSystems Container Registry, public and private images of such products as IRIS and IRIS for Health and many others in one place</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=caretdev/intersystems-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/caretdev/intersystems-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/caretdev/intersystems-extension" alt="Docker Pulls"></td></tr><tr><td>15</td><td>Ddosify</td><td>High-performance, open-source and simple load testing tool, written in Golang</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=ddosify/ddosify-docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/ddosify/ddosify-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/ddosify/ddosify-docker-extension" alt="Docker Pulls"></td></tr><tr><td>16</td><td>OpenShift</td><td>Easily deploy and test applications onto OpenShift</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=redhatdeveloper/openshift-dd-ext">Install</a></td><td><a href="https://hub.docker.com/extensions/redhatdeveloper/openshift-dd-ext">Link</a></td><td><img src="https://img.shields.io/docker/pulls/redhatdeveloper/openshift-dd-ext" alt="Docker Pulls"></td></tr><tr><td>17</td><td>Epinio</td><td>Push from source to Kubernetes in one step</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=splatform/epinio-docker-desktop">Install</a></td><td><a href="https://hub.docker.com/extensions/splatform/epinio-docker-desktop">Link</a></td><td><img src="https://img.shields.io/docker/pulls/splatform/epinio-docker-desktop" alt="Docker Pulls"></td></tr><tr><td>18</td><td>Jfrog</td><td>Scan your Docker images for vulnerabilities with JFrog Xray.</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=jfrog/jfrog-docker-desktop-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/jfrog/jfrog-docker-desktop-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/jfrog/jfrog-docker-desktop-extension" alt="Docker Pulls"></td></tr><tr><td>19</td><td>vcluster</td><td>Manage your vclusters running on docker-desktop.</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=loftsh/vcluster-dd-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/loftsh/vcluster-dd-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/loftsh/vcluster-dd-extension" alt="Docker Pulls"></td></tr><tr><td>20</td><td>Newman</td><td>Run your Postman collections from Docker Desktop</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=joycelin79/newman-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/joycelin79/newman-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/joycelin79/newman-extension" alt="Docker Pulls"></td></tr><tr><td>21</td><td>Lens</td><td>Run Lens Kubernetes on your Docker Desktop</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=k8slens/lens-dd-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/k8slens/lens-dd-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/k8slens/lens-dd-extension" alt="Docker Pulls"></td></tr><tr><td>22</td><td>Microcks</td><td>API Mocking and Testing for REST, GraphQL, gRPC and AsyncAPI</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=microcks/microcks-docker-desktop-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/microcks/microcks-docker-desktop-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/microcks/microcks-docker-desktop-extension" alt="Docker Pulls"></td></tr><tr><td>23</td><td>Open Source management tool for PostgreSQL</td><td>Docker Extension for using an embedded PGAdmin4 Open Source management tool for PostgreSQL</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=mochoa/pgadmin4-docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/mochoa/pgadmin4-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/mochoa/pgadmin4-docker-extension" alt="Docker Pulls"></td></tr><tr><td>24</td><td>Mini Cluster</td><td>"Mini Cluster" enables you run a local Apache Mesos cluster</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=avhost/docker-mesos-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/avhost/docker-mesos-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/avhost/docker-mesos-extension" alt="Docker Pulls"></td></tr><tr><td>25</td><td>Gosh</td><td>Build your decentralized and secure software supply chain with Docker and Git Open Source Hodler</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=teamgosh/docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/teamgosh/docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/teamgosh/docker-extension" alt="Docker Pulls"></td></tr><tr><td>26</td><td>Drone CI</td><td>Run Continuous Integration &#x26; Delivery Pipelines (CI/CD) from within Docker Desktop.</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=drone/drone-ci-docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/drone/drone-ci-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/drone/drone-ci-docker-extension" alt="Docker Pulls"></td></tr><tr><td>27</td><td>Aqua Trivy</td><td>Run unlimited vulnerability scans against remote or locally stored images</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=aquasec/trivy-docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/aquasec/trivy-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/aquasec/trivy-docker-extension" alt="Docker Pulls"></td></tr><tr><td>28</td><td>Meshery</td><td>Meshery is the open source, cloud native manager that enables the adoption, operation, and management of Kubernetes, any service mesh, and their workloads.</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=meshery/docker-extension-meshery">Install</a></td><td><a href="https://hub.docker.com/extensions/meshery/docker-extension-meshery">Link</a></td><td><img src="https://img.shields.io/docker/pulls/meshery/docker-extension-meshery" alt="Docker Pulls"></td></tr><tr><td>29</td><td>Oracle SQLcl client tool</td><td>Docker Extension for using an embedded version of Oracle SQLcl client tool</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=mochoa/sqlcl-docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/mochoa/sqlcl-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/mochoa/sqlcl-docker-extension" alt="Docker Pulls"></td></tr><tr><td>30</td><td>Tailscale</td><td>Tailscale lets you securely connect to your Docker containers without exposing them to the public internet.</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=tailscale/docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/tailscale/docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/tailscale/docker-extension" alt="Docker Pulls"></td></tr><tr><td>31</td><td>Akita API</td><td>Drop in Agent for API Monitoring and Observability</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=akitasoftware/akita-docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/akitasoftware/akita-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/akitasoftware/akita-docker-extension" alt="Docker Pulls"></td></tr><tr><td>32</td><td>Dive-In</td><td>Explore docker images, layer contents, and discover ways to shrink the size of your Docker/OCI image</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=prakhar1989/dive-in">Install</a></td><td><a href="https://hub.docker.com/extensions/prakhar1989/dive-in">Link</a></td><td><img src="https://img.shields.io/docker/pulls/prakhar1989/dive-in" alt="Docker Pulls"></td></tr><tr><td>33</td><td>Harpoon</td><td>Docker Extension for the No Code Kubernetes platform</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=harpooncorp/harpoon-ext">Install</a></td><td><a href="https://hub.docker.com/extensions/harpooncorp/harpoon-ext">Link</a></td><td><img src="https://img.shields.io/docker/pulls/harpooncorp/harpoon-ext" alt="Docker Pulls"></td></tr><tr><td>34</td><td>Localstack</td><td>Extension of Localstack for Docker desktop</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=localstack/localstack-docker-desktop">Install</a></td><td><a href="https://hub.docker.com/extensions/localstack/localstack-docker-desktop">Link</a></td><td><img src="https://img.shields.io/docker/pulls/localstack/localstack-docker-desktop" alt="Docker Pulls"></td></tr><tr><td>35</td><td>Alfresco Community</td><td>Alfresco Docker Extension</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=angelborroy/alfresco-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/angelborroy/alfresco-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/angelborroy/alfresco-extension" alt="Docker Pulls"></td></tr><tr><td>36</td><td>Kubescape</td><td>Kubescape is a multi-cloud Kubernetes and CI/CD security single pane of glass. Features include: risk analysis, security compliance, RBAC visualization, misconfiguration and image vulnerability scanning.</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=vklokun/docker-desktop-extension&#x26;tag=0.1.0">Install</a></td><td><a href="https://hub.docker.com/extensions/vklokun/docker-desktop-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/vklokun/docker-desktop-extension" alt="Docker Pulls"></td></tr><tr><td>37</td><td>NebulaGraph</td><td>Easily deploy and test NebulaGraph, the Open-Source Distributed Graph Database</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=weygu/nebulagraph-dd-ext">Install</a></td><td><a href="https://hub.docker.com/extensions/weygu/nebulagraph-dd-ext">Link</a></td><td><img src="https://img.shields.io/docker/pulls/weygu/nebulagraph-dd-ext" alt="Docker Pulls"></td></tr><tr><td>38</td><td>Gefyra</td><td>Gefyra's Docker extension to bridge running containers into Kubernetes clusters</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=gefyrahq/gefyra-docker-desktop-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/gefyra/docker-desktop-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/gefyra/docker-desktop-extension" alt="DockerPull"></td></tr><tr><td>39</td><td>Dockerfile-diff</td><td>Diff local or remotes images so you can more easily see the differences in their Dockerfiles</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=felipecruz/dockerfile-diff-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/felipecruz/dockerfile-diff-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/felipecruz/dockerfile-diff-extension" alt="DockerPull"></td></tr><tr><td>40</td><td>Dive Into Ansible</td><td>Run a Full Ansible Lab Environment within Docker Desktop!</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=spurin/diveintoansible-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/spurin/diveintoansible-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/spurin/diveintoansible-extension" alt="DockerPull"></td></tr><tr><td>41</td><td>Oracle SQLDeveloper Web</td><td>Docker Extension for using an embedded version of Oracle SQLDeveloper Web.</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=weygu/nebulagraph-dd-ext">Install</a></td><td><a href="https://hub.docker.com/extensions/mochoa/sdw-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/mochoa/sdw-docker-extension" alt="DockerPull"></td></tr><tr><td>42</td><td>Grafana</td><td>Monitor your docker desktop instance from Grafana cloud.</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=grafana/docker-desktop-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/grafana/docker-desktop-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/grafana/docker-desktop-extension" alt="DockerPull"></td></tr><tr><td>43</td><td>Remote.it</td><td>Docker desktop extension to easily connect to containers from anywhere</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=remoteit/docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/remoteit/docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/remoteit/docker-extension" alt="DockerPull"></td></tr><tr><td>44</td><td>ContainerWatch</td><td>ContainerWatch is an extension that adds feature-rich monitoring tools to Docker Desktop.</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=containerwatch/docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/containerwatch/containerwatch">Link</a></td><td><img src="https://img.shields.io/docker/pulls/containerwatch/containerwatch" alt="DockerPull"></td></tr><tr><td>45</td><td>Kafka Sonar</td><td>This is the one-stop shop Docker Desktop Extension for seamless Kafka cluster monitoring and troubleshooting 🐋.</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=oslabs-beta/kafkasonar">Install</a></td><td><a href="https://hub.docker.com/extensions/kafkasonar/kafkasonar">Link</a></td><td><img src="https://img.shields.io/docker/pulls/kafkasonar/kafkasonar" alt="DockerPull"></td></tr><tr><td>46</td><td>Docketeer-extension</td><td>This is A Docker &#x26; Kubernetes developer tool to manage containers &#x26; visualize both cluster and container metrics</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=oslabs-beta/kafkasonar">Install</a></td><td><a href="https://hub.docker.com/extensions/kafkasonar/kafkasonar">Link</a></td><td><img src="https://img.shields.io/docker/pulls/kafkasonar/kafkasonar" alt="DockerPull"></td></tr><tr><td>47</td><td>VS Code for the Web</td><td>Docker Extension for using an embedded VS Code for the Web</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=mochoa/coder-docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/mochoa/coder-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/mochoa/coder-docker-extension" alt="DockerPull"></td></tr><tr><td>48</td><td>PortNavigator</td><td>Networking Tool for network visualization and configurations</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=portnavigator/port-navigator">Install</a></td><td><a href="https://hub.docker.com/extensions/portnavigator/port-navigator">Link</a></td><td><img src="https://img.shields.io/docker/pulls/portnavigator/port-navigator" alt="DockerPull"></td></tr><tr><td>49</td><td>Jupyter Notebook Scientific Python Stack</td><td>Docker Extension for using an embedded Jupyter Notebook Scientific Python Stack</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=mochoa/jupyter-docker-extension">Install</a></td><td><a href="https://hub.docker.com/extensions/mochoa/jupyter-docker-extension">Link</a></td><td><img src="https://img.shields.io/docker/pulls/mochoa/jupyter-docker-extension" alt="DockerPull"></td></tr><tr><td>50</td><td>Warp Docker Extension</td><td>Warp Docker Extension</td><td><a href="https://open.docker.com/extensions/marketplace?extensionId=warpdotdev/warp:0.0.23">Install</a></td><td><a href="https://hub.docker.com/extensions/warpdotdev/warp">link</a></td><td><img src="https://img.shields.io/docker/pulls/warpdotdev/warp" alt="DockerPull"></td></tr></tbody></table>

