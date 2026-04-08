# Contributing Guidelines

Thank you for considering a contribution to this project!  We welcome bug reports, feature requests, new notebooks and documentation improvements.  By participating in this project you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

## How to contribute

1. **Fork** the repository and clone your fork locally.
2. Create a new branch for your change (`git checkout -b feature/my‑new‑feature`).
3. Make your changes and commit them with clear, descriptive commit messages.
4. Push your branch to your fork and open a **pull request** against the `main` branch of this repository.
5. In your pull request description, explain what the change does and link any relevant issues.

### Types of contributions

- **Bug fixes**: If you find an error in one of the notebooks (code does not run, incorrect explanation, etc.), open an issue or directly submit a fix.
- **New notebooks**: New examples on algorithms or techniques are welcome.  Follow the style of existing notebooks: include comments, markdown cells explaining the theory, and plots illustrating results.  Place datasets in the `datasets/` directory or link to publicly available sources.
- **Improvements**: You can enhance existing notebooks by adding commentary, visualisations or alternative approaches.  You can also refine the README, contributing guidelines or other documentation.
- **Translations**: Feel free to add translated versions of notebooks or the README.  Place translations in a separate directory named after the language code (e.g., `notebooks/es/`).

## Development environment

We recommend using **Python 3.10** or newer.  Install dependencies from the `requirements.txt` file and launch Jupyter Lab or Jupyter Notebook.  Ensure that your notebook runs from top to bottom before opening a pull request.

```bash
pip install -r requirements.txt
jupyter lab
```

## Reporting issues

If you have a question or find a bug, please open an issue on GitHub.  Provide as much context as possible: operating system, Python version, error messages and steps to reproduce.  A clear, reproducible example helps maintainers address problems quickly.

## Code style

While Jupyter notebooks can be free‑form, please strive to follow the [PEP 8](https://peps.python.org/pep‑0008/) coding style for Python code cells.  Use descriptive variable names and comment your logic where it might not be obvious.

## License

By contributing to this project, you agree that your contributions will be licensed under the project’s [MIT License](LICENSE).