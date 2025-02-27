# CLAUDE.md - Project Guide

## Project Overview
This is a basic Node.js application with Express running in Docker.

## Useful Commands

### Docker Commands
```bash
# Build Docker image
docker build -t basic-node-app .

# Run Docker container
docker run -d -p 3000:3000 --name basic-node-container basic-node-app

# Stop Docker container
docker stop basic-node-container

# Remove Docker container
docker rm basic-node-container

# View running containers
docker ps

# View container logs
docker logs basic-node-container
```

### Development Commands
```bash
# Install dependencies
npm install

# Start application locally
npm start
```

### Git Commands
```bash
# Add files
git add .

# Commit changes
git commit -m "Commit message"

# Push changes
git push origin master
```

## Project Structure
- `index.js` - Main application entry point
- `package.json` - Node.js dependencies and scripts
- `Dockerfile` - Docker image configuration
- `README.md` - Project documentation
- `CLAUDE.md` - This file, containing useful project commands and information