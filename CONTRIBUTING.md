# Contribution Guide for Zango

## Table of Contents
1. [How to Contribute](#how-to-contribute)
    - [Reporting Issues](#reporting-issues)
    - [Contributing to Zango](#contributing-to-zango)
2. [Contributing to Zango backend](#contributing-to-zango-backend)
3. [Contributing to frontend](#contributing-to-frontend)
4. [Contributing to documentation](#contributing-to-documentation)


## How to Contribute

### Reporting Issues
If you find a bug or have a feature request, please create an issue in our [issue tracker](https://github.com/Healthlane-Technologies/Zango/issues). When reporting an issue, please include as much detail as possible, including steps to reproduce the problem, your environment, and any relevant log output.

## Contributing to Zango

This section describes the general practices for contributing to zango, you can check the next sections which describe how to contribute to frontend, backend and documentation

### Getting Started
1. **Fork the Repository**: Fork the [Zango repository](https://github.com/Healthlane-Technologies/Zango) to your GitHub account.
2. **Clone the Repository**: Clone your forked repository to your local machine.
3. Set Up Environment: Follow the setup instructions in Setup.md to configure your development environment.

### Development Workflow

1. Create a Branch: Create a new branch for your feature or bugfix
```bash
    git checkout -b feature/your-feature-name
```
2. Implement Changes: Make your changes, ensuring to follow the coding standards and best practices.
3. Commit Changes: Commit your changes with a meaningful commit message.
```bash
    git add .
    git commit -m "Add feature <feature_name>"
```

### Submitting Changes
1. Push to GitHub: Push your changes to your forked repository.
```bash
    git push origin feature/your-feature-name
```
2. Create a Pull Request: Open a pull request from your branch to the main branch of the original repository. Provide a clear description of your changes and link any related issues.

### Code Review
1. Respond to Feedback: Be prepared to make changes based on feedback from code reviewers.
2. Update PR: Push any updates to your branch to reflect the feedback received.

## Contributing to Zango backend

### Steps to contribute to Zango backend
1. Clone the zango repository
2. Create a new virtual environment
3. From the `zango/backend` directory run the following command
```bash
    pip install -e .
```
4. Perform the steps to setup a new project as described in the docs [here](https://www.zango.dev/docs/core/getting-started/installing-zelthy/manual#zango-the-zango-cli)
5. Start you project
6. Make changes to Zango and view the changes in your project.
7. Create a Pull request in the Zango repository.

## Contributing to frontend

## Contributing to Documentation

