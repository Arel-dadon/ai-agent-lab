# Architecture

This document describes the structure of the repository.

## Directory Structure

*   **/frontend**: Contains the frontend application code, which handles user interfaces and interactions.
*   **/backend**: Contains the backend application code, including API routes, database logic, and core business functionality.
*   **/tests**: Contains test suites to ensure code reliability. It houses unit, integration, and end-to-end tests for both frontend and backend logic.
*   **/scripts**: Contains utility scripts for operations, deployment, setup, and other repetitive tasks.
*   **/docs**: Contains project documentation, such as architectural overviews, API documentation, and agent instructions.

## GitHub Workflow Expectations

*   **Branching**: All work must happen on feature branches. Direct commits to `main` are not allowed.
*   **Pull Requests**: Changes must be submitted via Pull Requests.
*   **CI/CD**: CI workflows are expected to run on pull requests. These pipelines will validate code through testing and linting to ensure quality before changes are merged.
