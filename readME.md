
---

### 📖 `README.md`

```markdown
# Simple Python Project

This is a minimal Python project featuring basic math functions, unit tests, and GitHub Actions CI.

## Features

- Basic math operations (add, subtract)
- Unit tests with `pytest`
- CI pipeline using GitHub Actions

## Getting Started

### Prerequisites

Ensure you have Python and `pytest` installed on your system.

On most Debian/Ubuntu-based Linux distros:

```bash
sudo apt update
sudo apt install python3 python3-pytest
```

> You can check your installation with:
> ```bash
> python3 --version
> pytest --version
> ```

### Running the Tests

To run the test suite, execute:

```bash
pytest
```

This will run all test files located in the `tests/` directory.

---

## GitHub Actions CI

This project includes a GitHub Actions workflow that:

- Runs on every `push` and `pull request`
- Tests against multiple Python versions (3.8–3.11)
- Uses `pytest` to run the test suite

You can find the workflow file under `.github/workflows/python-ci.yml`.

---

## Project Structure

```
simple-python-project/
├── my_app/
│   └── math_utils.py
├── tests/
│   └── test_math_utils.py
├── .github/workflows/python-ci.yml
├── requirements.txt
├── README.md
└── .gitignore
```

---

## License

MIT


