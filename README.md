# Docker Host Setup and WordPress Installation on Docker

In this project, I successfully set up a Docker host and installed WordPress on Docker using the following steps:

## Project Overview

The project involved setting up a Docker host and deploying WordPress on Docker. Key configurations included:

- **Docker Installation:** Installed Docker on the host machine.

- **Docker Network Setup:** Created a Docker network for WordPress and MySQL containers to communicate.

- **Persistent Storage:** Created a Docker volume to persist WordPress data.

- **Image Pulling:** Pulled the latest WordPress and MySQL Docker images from the Docker Hub registry.

- **MySQL Container Configuration:** Created a MySQL container with a root password and a database for WordPress.

- **WordPress Container Configuration:** Created a WordPress container with environment variables for the database connection and site configuration.

- **Network and Volume Attachment:** Attached the WordPress container to the Docker network and volume.

- **Container Start and Verification:** Started the containers and verified that WordPress was running on Docker by accessing it through a web browser.

## Deployment Process

The deployment process focused on creating a Dockerized environment for hosting WordPress, ensuring efficient container communication and persistent storage.

## Verification

After completing these steps, the WordPress website was successfully installed and running on Docker, with MySQL serving as the database backend.

## Technology Stack

- **Docker:**
  - Docker Engine
  - Docker Compose

- **WordPress Stack:**
  - WordPress
  - MySQL

## Conclusion

This deployment demonstrated the successful setup and installation of WordPress on Docker, providing a containerized environment for hosting a WordPress website with MySQL as the database backend.

