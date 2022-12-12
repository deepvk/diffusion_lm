# 🥜 Diffusion-LM

[![Main](https://github.com/deepvk/diffusion_lm/actions/workflows/main.yaml/badge.svg)](https://github.com/deepvk/diffusion_lm/actions/workflows/main.yaml)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Checked with mypy](http://www.mypy-lang.org/static/mypy_badge.svg)](http://mypy-lang.org/)

*Work in progress*

Reimplementation of ["Diffusion-LM Improves Controllable Text Generation"](https://arxiv.org/abs/2205.14217) paper.
Official implementation is available on GitHub: [`XiangLi1999/Diffusion-LM`](https://github.com/XiangLi1999/Diffusion-LM).

## Structure

- [`src`](./src) ‒ main source code with model and dataset implementations and code to train, test or infer model.
- [`scripts`](./scripts) ‒ different useful scripts, e.g. print dataset examples or evaluate existing models.
- [`tests`](./tests) ‒ tests.

## Requirements

Create virtual environment with `venv` or `conda` and install requirements:
```bash
pip install -r requirements.txt
```

For proper contributions, also use dev requirements:
```bash
pip install -r requirements-dev.txt
```

