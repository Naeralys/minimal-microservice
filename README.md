# Minimalistic .Net 6 Microservice

Just a test template where two microservices are running (CompanyApi and UserApi).
The goal was to discover how quickly such an architecture could be built using the last .Net version, running each microservices in a Docker container and orchestrated with docker-compose.

## Install
Not sure if .Net 6 SDK is needed, or if docker resolves it through the mcr.microsoft.com/dotnet/sdk:6.0-alpine package.

```bash
docker-compose build
```

```bash
docker-compose up
```

## Usage

``localhost:3001/`` will just render a "list of companies" string

``localhost:3002/`` will just render a "list of users" string