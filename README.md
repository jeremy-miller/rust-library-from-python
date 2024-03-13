# Rust Library From Python

Simple example of using [PyO3](https://pyo3.rs/) to call a Rust function from Python.

## Setup

*This code assumes both Rust and Python are installed.*

1. Create virtual environment: `python -m venv .venv`
2. Activate virtual environment: `source .venv/bin/activate`
3. Install requirements: `pip install -r requirements.txt`
4. Install the Rust package inside the Python virtualenv: `maturin develop`

## Run

To run the Python example: `python main.py`
