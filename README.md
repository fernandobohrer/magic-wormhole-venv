# magic-wormhole virtual environment

This repository creates a `python` based virtual environment using `uv` and automatically installs [`magic-wormhole`][01] into the environment.

## 🚀 Motivation

The virtual environment created by this repository is designed to provide an easy way to use the [`magic-wormhole`][01] solution.

The main advantage of using a virtual environment is its ability to isolate dependencies, ensuring that the packages listed in the `pyproject.toml` file won't interfere with or affect other packages installed on your system.

## 🧰 Dependencies

- [uv][02]

Refer to your operating system's package manager or documentation to install the dependencies on your machine.

## ⚡ Quick start

1. To create and initialize the `python` based virtual environment, run `make bootstrap`.

1. Switch to any directory in which you want to use the `wormhole` command to actually use the solution.

1. When you are finished with your work, simply exit the virtual environment by typing `exit` in the terminal. This will bring you back to the directory where this repository is located.

1. To completely remove the virtual environment, run `make cleanup`.

## 📝 License

This project is licensed under the terms of the [MIT license][03].

[01]: https://magic-wormhole.readthedocs.io/en/latest/
[02]: https://docs.astral.sh/uv/
[03]: /LICENSE
