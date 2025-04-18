# Contributing to JavaFX Quiz App

Thank you for considering contributing to the **JavaFX Quiz App**! We welcome contributions from the community to improve this open-source project. This document outlines the process for contributing, including reporting bugs, suggesting features, and submitting code changes.

## 🚀 Getting Started

Before contributing, please familiarize yourself with the project by reading the [README.md](README.md) and exploring the codebase. Ensure you have the necessary development environment set up as described in the README.

### Code of Conduct

All contributors are expected to adhere to our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it to understand the expectations for respectful and inclusive collaboration.

## 🐛 Reporting Bugs

If you find a bug, please report it by opening an issue on the [GitHub Issues page](https://github.com/VoxDroid/Java-Quiz-App/issues). When submitting a bug report, include:

- A clear and descriptive title.
- Steps to reproduce the issue.
- Expected and actual behavior.
- Screenshots or logs, if applicable.
- Your environment (e.g., Java version, JavaFX version, OS).

Use the bug report template provided when opening a new issue.

## 💡 Suggesting Features

We welcome ideas for new features or improvements! To suggest a feature:

1. Open an issue on the [GitHub Issues page](https://github.com/VoxDroid/Java-Quiz-App/issues).
2. Use the feature request template.
3. Provide a detailed description of the proposed feature and its benefits.
4. If possible, suggest how it could be implemented.

## 🔨 Submitting Code Changes

To contribute code, follow these steps:

### 1. Fork the Repository

1. Fork the repository by clicking the "Fork" button on the [GitHub repository page](https://github.com/VoxDroid/Java-Quiz-App).
2. Clone your fork to your local machine:

   ```bash
   git clone https://github.com/<your-username>/Java-Quiz-App.git
   ```

3. Create a new branch for your changes:

   ```bash
   git checkout -b feature/your-feature-name
   ```

### 2. Make Changes

- Follow the project's coding standards (see below).
- Ensure your changes are focused and address a single issue or feature.
- Write clear, concise commit messages.

### 3. Coding Standards

- **Language**: Use Java 17 with JavaFX 11+.
- **Formatting**: Follow the default IntelliJ IDEA code style for Java.
- **Documentation**: Add Javadoc comments for public methods and classes.
- **Testing**: Include unit tests using JUnit for new functionality.
- **Database**: Ensure SQLite database operations are safe and efficient.
- **Localization**: Support multilingual strings using the `messages.properties` files.

### 4. Test Your Changes

- Run the application locally to verify your changes:

  ```bash
  mvn javafx:run
  ```

- Run existing tests:

  ```bash
  mvn test
  ```

- Add new tests for your changes, if applicable.

### 5. Submit a Pull Request

1. Push your changes to your fork:

   ```bash
   git push origin feature/your-feature-name
   ```

2. Open a pull request (PR) on the [GitHub Pull Requests page](https://github.com/VoxDroid/Java-Quiz-App/pulls).
3. Use the [pull request template](PULL_REQUEST_TEMPLATE.md) provided.
4. Describe your changes, including the problem solved or feature added.
5. Reference any related issues (e.g., `Fixes #123`).

### 6. Review Process

- Maintainers will review your PR and provide feedback.
- Be responsive to comments and make requested changes.
- Once approved, your changes will be merged into the main branch.

## 📚 Resources

- [JavaFX Documentation](https://openjfx.io/)
- [SQLite JDBC Driver](https://github.com/xerial/sqlite-jdbc)
- [Maven Documentation](https://maven.apache.org/)
- [IntelliJ IDEA Documentation](https://www.jetbrains.com/idea/documentation/)

## 🙏 Acknowledgments

Thank you for your interest in contributing to the JavaFX Quiz App! Your efforts help make this project better for everyone.

<p align="center">
  <a href="https://ko-fi.com/O4O6LO7Q1" target="_blank">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="ko-fi" style="border: 0;">
  </a>
</p>