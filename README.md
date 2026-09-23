# PSU Calculator

Archived PSU calculator project from the Vigiatonet organization.

The repository contains a static frontend and a Go backend/API. The backend includes Docker-related infrastructure and logging/configuration code.

## Technology

- HTML, CSS, JavaScript frontend
- Go backend
- Gin, GORM, Redis, JWT, Swagger-related Go dependencies
- Docker/ELK configuration under the backend tree

## Structure

- `index.html`, `style.css`, `main.js` - Static frontend files.
- `backend/src/` - Go backend source.
- `backend/docker/` - Historical Docker/ELK support files.
- `backend/docker/.env.example` - Sanitized example environment variables.

## Status

Archived project. The original runtime `.env` file was removed from the public working tree and replaced with a sanitized example. No dependency upgrades or modernization have been performed.
