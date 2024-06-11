ARG VARIANT=debian-12
FROM mcr.microsoft.com/vscode/devcontainers/base:${VARIANT}

ARG NONINTERACTIVE=1
RUN sudo apt-get update && \
    sudo apt-get install -y \
      build-essential \
      curl \
      file \
      gcc \
      git \
      procps ;