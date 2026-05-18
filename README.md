# Devops_project

This repository contains a simple DevOps-focused web application with separate frontend and backend components.

## Project structure

- `backend/` - Node.js server and backend tests
- `frontend/` - Static frontend files
- `Dockerfile` - Docker image build configuration
- `Jenkinsfile` - CI/CD pipeline definition

## Backend

The backend is a Node.js application located in `backend/`.

### Run locally

```bash
cd backend
npm install
node server.js
```

### Test

```bash
cd backend
npm test
```

## Frontend

The frontend is a static web app in `frontend/`.

### Run locally

Open `frontend/index.html` in a browser, or use any static server.

## Docker

Build the Docker image:

```bash
docker build -t devops_project .
```

## CI/CD

This repository includes a `Jenkinsfile` and GitHub workflow for automated builds and deployments.

## License

This project does not include a license file. Add one if you want to specify usage terms.
