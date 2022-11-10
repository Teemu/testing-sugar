ARG VARIANT="3"
FROM mcr.microsoft.com/vscode/devcontainers/python:0-${VARIANT}

RUN pip --disable-pip-version-check --no-cache-dir install -e '.[dev]' && pre-commit install
