# Basic Node.js Docker Application

A simple Node.js application with Express running in Docker.

## Prerequisites

- [Docker](https://www.docker.com/get-started)
- [Node.js](https://nodejs.org/) (only needed for local development)

## Getting Started

### Building the Docker Image

```bash
docker build -t basic-node-app .
```

### Running the Container

```bash
docker run -d -p 3000:3000 --name basic-node-container basic-node-app
```

The application will be available at [http://localhost:3000](http://localhost:3000).

### Stopping the Container

```bash
docker stop basic-node-container
```

### Removing the Container

```bash
docker rm basic-node-container
```

## Project Structure

- `index.js` - Main application entry point
- `package.json` - Node.js dependencies and scripts
- `Dockerfile` - Docker image configuration

## Local Development

To run the application locally without Docker:

```bash
npm install
npm start
```