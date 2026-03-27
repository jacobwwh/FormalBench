# FormalBench: A Comprehensive Evaluation of LLMs on Formal Specification Inference

## Prerequisites

FormalBench have two modes:
- Docker mode, which requires the docker in your local computers
- Non-Docker mode, which requires Ubuntu 20.04

Versions:
- Python 3.12
- Pip 25.0
- Java 11
- Clang-12

## Installation

- Create virtual environment with Python (default version of FormalBench is Python 3.12)
```
python3 -m venv .env
. .env/bin/activate
```

- Install FormalBench
```
pip3 install -e .[default]
```
