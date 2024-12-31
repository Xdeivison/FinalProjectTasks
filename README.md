
# Final Project Repository

This repository contains the final project implementation.

## Structure

- `.github/workflows/ci-build.yaml`: Defines the CI/CD workflow.
- `Dockerfile`: Configuration for building the Docker image.
- `requirements.txt`: Lists Python dependencies.
- `app.py`: A simple Flask application for demonstration.
- `README.md`: This file describing the repository.

## How to Run Locally

1. Clone the repository.
2. Install Python dependencies with `pip install -r requirements.txt`.
3. Run the Flask app using `python app.py`.

## How to Build Docker Image

1. Build the image: `docker build -t final_project .`
2. Run the container: `docker run -p 5000:5000 final_project`.
