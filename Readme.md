## FastAPI CI/CD Pipeline Project

This project is a minimal FastAPI application designed to demonstrate a simple CI/CD pipeline using GitHub Actions and Docker. The application exposes a single root endpoint and includes automated tests to ensure functionality. The CI workflow installs dependencies, runs tests, and builds a Docker image on every push or pull request to the main branch.

**Key Features:**
- FastAPI web application with a root endpoint
- Automated testing using pytest
- Dockerized deployment
- GitHub Actions workflow for CI/CD

**Project Structure:**
- `app/main.py`: FastAPI application code
- `app/test_main.py`: Automated tests for the API
- `Dockerfile`: Containerization setup
- `.github/workflows/ci.yml`: GitHub Actions workflow for CI/CD

---
