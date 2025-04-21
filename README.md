# GitHub Actions Docker CI/CD

This project demonstrates a CI/CD pipeline using GitHub Actions to:
- Build a Docker image for a Python Flask app.
- Push the image to DockerHub.

## Workflow Overview:
- Trigger: Push to `main` branch.
- Steps: Checkout → Docker Login → Build → Push.

## Requirements:
- DockerHub account.
- GitHub Actions secrets: `DOCKERHUB_USERNAME`, `DOCKERHUB_PASSWORD`.

---

Happy DevOps 🚀
