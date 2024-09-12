# Hosting a Windows App Using Docker

## Commands

This guide provides the essential commands to build and run your Docker containers for a Windows application.

### 1. Build the Docker Image

To build the Docker image based on the `Dockerfile` in your directory:

```bash
docker-compose build
```

Explanation:

docker-compose build: This command reads the docker-compose.yml file and builds the Docker images specified in it. It will use the Dockerfile to set up the container's environment, install dependencies, and prepare the application.
2. Start the Docker Containers
To start and run the Docker containers:

```bash
docker-compose up
```
Explanation:

docker-compose up: This command starts up the services defined in the docker-compose.yml file. It will create and start containers for each service (e.g., your application and database). If the containers are not already built, it will also build them first.
3. Run Containers in Detached Mode
To start the Docker containers in the background (detached mode):

```bash
docker-compose up -d
```
Explanation:

-d: This flag stands for "detached mode." It allows the containers to run in the background, freeing up your terminal.
4. Check Container Logs
To view the logs of the running containers:



```bash
docker-compose down
```
Explanation:

docker-compose down: This command stops and removes the containers created by docker-compose up. It also removes any networks defined in the docker-compose.yml file.
6. View Container Status
To check the status of the running containers:
