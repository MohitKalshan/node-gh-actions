# node-gh-actions

A simple Node.js Express application with GitHub Actions deployment setup.

## Features

- Express server
- JSON response on `/`
- Supports running with `npm start`

## Prerequisites

- Node.js 18+ (or compatible)
- npm

## Install

```bash
npm install
```

## Run locally

```bash
npm start
```

Then open http://localhost:3000 in your browser.

## Project structure

- `index.js` - Application entry point
- `package.json` - Project metadata and scripts
- `Dockerfile` - Docker image build file
- `docker-compose.yml` - Docker Compose service configuration
- `.github/workflows/deploy.yaml` - GitHub Actions deployment workflow

## Notes

The server responds with JSON:

```json
{ "message": "Hello World!" }
```
