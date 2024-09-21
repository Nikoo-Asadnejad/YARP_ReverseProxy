# YARP Reverse Proxy & API Gateway in .NET 8

This repository contains a reverse proxy and API gateway implementation using YARP (Yet Another Reverse Proxy) in .NET 8. The project is containerized with Docker and orchestrated using Docker Compose.

## Features

- **YARP (Yet Another Reverse Proxy)**: Configured for routing API requests to multiple backend services.
- **API Gateway**: Centralized API management, routing requests to different services based on defined routes.
- **Docker**: The application is containerized for easy deployment.
- **Docker Compose**: Orchestrates the reverse proxy and multiple backend services.
- **Scalability**: Easy to add new services and update routing rules via configuration.