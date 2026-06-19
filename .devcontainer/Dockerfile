FROM mcr.microsoft.com/devcontainers/miniconda:3

COPY environment.yml /tmp/
RUN conda env create -f /tmp/environment.yml \
    && conda clean --all -y