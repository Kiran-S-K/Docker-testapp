# docker-testapp
## Overview  
This project demonstrates how to deploy and manage a MongoDB database using Docker and Docker Compose. The setup includes a MongoDB container for database storage and a Mongo Express container for web-based database administration.

The containers communicate through Docker’s custom bridge network, allowing services to discover each other using container names instead of IP addresses. A Docker volume is attached to the MongoDB container to ensure data persistence even after containers are stopped or removed.  

Environment variables are used to configure database credentials and connection details, following best practices for security and flexibility. This project reflects a real-world database setup commonly used in development environments.  

## Why This Project?

-To understand Docker volumes and persistent storage

-To learn container-to-container communication

-To practice real-world database deployment using Docker

-To explore service orchestration with Docker Compose
