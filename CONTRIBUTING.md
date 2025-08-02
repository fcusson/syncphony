# Contributing to Syncphony

Thank you for your interest in contributing to **Syncphony**! This guide will help you get started with development, testing, and submitting contributions.

---

## 📦 Setting Up the Project

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/syncphony.git
cd syncphony
```

2. **Create and activate a virtual environment**

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -e .[dev]
```

4. **Install pre-commit hooks (optional but recommended)**

```bash
pre-commit install
```

---

## Contribution Types

We welcome many types of contributions, including:

* Bug reports and issue discussions
* Feature suggestions and design ideas
* Code for bug fixes or enhancements
* Documentation improvements
* Test cases and code cleanup

---

## Code Style

We use:

* **Ruff** for linting
* **isort** for import sorting
* **mypy** for type checking

You can run all checks with:

```bash
pre-commit run --all-files
```

---

## Submitting a Pull Request

1. Fork the repository
2. Create a new branch: `git checkout -b feature/my-feature`
3. Make your changes
4. Write or update tests if applicable
5. Ensure tests pass: `pytest`
6. Submit a pull request with a clear title and description

---

## Need Help?

If you're unsure how to proceed, feel free to open a discussion or issue. We're happy to guide you through your first contribution.

---

> Thank you for helping make Syncphony better!

