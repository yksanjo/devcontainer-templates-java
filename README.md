# Dev Container Template - Java

Pre-configured containerized development environment for Java applications with Spring Boot support.

## Features

- **Java 17** with OpenJDK
- **Maven** and **Gradle** support
- **Spring Boot Dashboard** for managing Spring applications
- **Java Test Runner** for JUnit testing
- **GitLens** for Git integration
- **SQLTools** for database management
- **XML** and **YAML** support

## Quick Start

1. Copy `.devcontainer` folder to your project root
2. Open the project in VS Code
3. Press `F1` and select **"Dev Containers: Reopen in Container"**

## Configuration

### Ports
- `3000` - Application server
- `5005` - Java debugger
- `8080` - Spring Boot default port
- `8443` - HTTPS port

### Extensions Included
- Java Debug
- Java Test
- Maven for Java
- Java Dependency
- Spring Boot Dashboard
- Docker
- PowerShell
- SQLTools
- IntelliCode
- GitLens
- XML
- YAML

### Post-Create Commands
- Shows Java version
- Shows Maven version

## Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [VS Code](https://code.visualstudio.com/)
- [Dev Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## License

MIT
