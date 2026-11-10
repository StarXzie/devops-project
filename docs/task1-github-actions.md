# Task 1: CI/CD with GitHub Actions + Docker

A Node.js (Express) app is tested, built into a Docker image and pushed to Docker Hub on every push to `main`.

- Repo: https://github.com/StarXzie/nodejs-demo-app
- Jobs: `test`, then `build-and-push` (`needs: test`)
- Docker Hub credentials are stored as GitHub Actions secrets, never in code
