# Cubit

A simple web application that calculates the cube of a given number.

## About

Cubit is a lightweight browser-based tool. Enter any number and click **Cube** to see the result displayed on screen.

## Getting Started

### Prerequisites

- A modern web browser
- A local HTTP server (e.g. Python's built-in server)

### Running the App

```bash
# Python 3
python -m http.server 8000
```

Then open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

## Testing

Tests are written with [Playwright](https://playwright.dev/python/).

### Install dependencies

```bash
pip install playwright
playwright install
```

### Run tests

```bash
pytest tests/
```

## Built With

- HTML / JavaScript
- [Bootstrap 5](https://getbootstrap.com/)
- [Playwright](https://playwright.dev/python/) (testing)

