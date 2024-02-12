# docker-playground

Playing with docker ...

## Introduction

Docker is an open-source platform that automates the deployment, scaling, and management of applications by isolating them into lightweight, portable containers. Containers are standalone executable units that encapsulate all necessary dependencies, libraries, and configuration files required for an application to run consistently across various environments.

### 1. [What are Containers](docs/introduction/whatAreContainers.md)

### 2. [Need for Containers](docs/introduction/needForContainers.md)

### 3. [Bare Metal vs VM vs Containers](docs/introduction/bm-vm-container.md)

### 4. [Docker & OCI](docs/introduction/oci.md)

## Underlying Technologies

Understanding the core technologies that power Docker will provide you with a deeper insight into how Docker works and will help you use the platform more effectively.

### 1. [Linux Containers (LXC)](docs/underlyingTech/linuxContainers.md)

### 2. [Namespaces](docs/underlyingTech/namespaces.md)

### 3. [Control Groups](docs/underlyingTech/controlGroups.md)

### 4. [Union FileSystems](docs/underlyingTech/unionFileSystems.md)

## Installation / Setup

Docker provides a desktop application called Docker Desktop that simplifies the installation and setup process. There is also another option to install using the Docker Engine.

### 1. [Docker Desktop](docs/installation-setup/dockerDesktop.md)

### 2. [Docker Engine](docs/installation-setup/dockerEngine.md)

## [Docker Basics](docs/dockerBasics/dockerBasics.md)

## [Data Persistence](docs/dataPersistence/dataPersistance.md)

### 1. [Ephemeral container filesystem](docs/dataPersistence/ephemeralFS.md)

### 2. [Volume Mounts](docs/dataPersistence/volumeMounts.md)

### 3. [Bind Mounts](docs/dataPersistence/bindMounts.md)

## [Using 3rd Party Container Images](docs/thirdPartyImages/usingThirdPartyImages.md)

### 1. [Databases](docs/thirdPartyImages/databases.md)

### 2. [Interactive Test Environments](docs/thirdPartyImages/interactiveTestEnvironments.md)

### 3. [Command Line Utilities](docs/thirdPartyImages/commandLineUtilities.md)

## [Building Container Images](docs/buildingContainerImages/buildingContainerImages.md)

### 1. [Dockerfiles](docs/buildingContainerImages/dockerfiles.md)

### 2. [Efficient layer caching](docs/buildingContainerImages/efficientLayerCaching.md)

### 3. [Image size and security](docs/buildingContainerImages/imageSizeAndSecurity.md)

## [Container Registries](docs/containerRegistries/containerRegistries.md)

### 1. [DockerHub](docs/containerRegistries/dockerHub.md)

### 2. [DockerHub Alternatives](docs/containerRegistries/dockerHubAlternatives.md)

### 3. [Image Tagging Best Practices](docs/containerRegistries/imageTaggingBestPractices.md)

## [Running Containers](docs/runningContainers/runningContainers.md)

### 1. [Docker Run](docs/runningContainers/dockerRun.md)

### 2. [Docker Compose](docs/runningContainers/dockerCompose.md)

### 3. [Runtime Configuration Options](docs/runningContainers/runtimeConfigurationOptions.md)

## [Container Security](docs/containerSecurity/containerSecurity.md)

### 1. [Image Security](docs/containerSecurity/imageSecurity.md)

### 2. [Runtime Security](docs/containerSecurity/runtimeSecurity.md)

## [Docker CLI](docs/dockerCLI/dockerCLI.md)

### 1. [Images](docs/dockerCLI/images.md)

### 2. [Containers](docs/dockerCLI/containers.md)

### 3. [Networks](docs/dockerCLI/networks.md)

### 4. [Volumes](docs/dockerCLI/volumes.md)

## [Developer Experience](docs/developerExperience/developerExperience.md)

### 1. [Hot Reloading](docs/developerExperience/hotReloading.md)

### 2. [Debuggers](docs/developerExperience/debuggers.md)

### 3. [Tests](docs/developerExperience/tests.md)

### 4. [Continuous Integration](docs/developerExperience/ci.md)

## [Deploying Containers](docs/deployingContainers/deployingContainers.md)

### 1. [PaaS Options](docs/deployingContainers/PaaSOptions.md)

### 2. [Kubernetes](docs/deployingContainers/kubernetes.md)

### 3. [Docker Swarm](docs/deployingContainers/dockerSwarm.md)

### 4. [Nomad](docs/deployingContainers/nomad.md)
