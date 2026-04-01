# CI/CD Testing Demo

A simple Python application demonstrating a CI/CD pipeline with automated testing using GitHub Actions.

## Tech Stack

- Python (Flask)
- Pytest
- GitHub Actions

## Project Structure

ci-cd-testing-demo/
├── app/
│   ├── __init__.py
│   └── app.py
├── tests/
│   └── test_app.py
├── requirements.txt
├── .gitignore
└── .github/workflows/ci.yml

## How It Works

This project uses GitHub Actions to automatically:

- Install dependencies
- Run tests using pytest
- Validate code on every push

## Running Locally

```bash
pip install -r requirements.txt
pytest
```

## CI Pipeline

The pipeline is triggered on every push to the main branch and ensures that the application passes all tests before changes are accepted.

## Notes

This project demonstrates basic CI/CD principles and automated testing in a clean and minimal setup.
