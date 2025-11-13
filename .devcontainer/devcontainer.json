# syntax=docker/dockerfile:1
FROM mambaorg/micromamba:1.5.8

ENV MAMBA_DOCKERFILE_ACTIVATE=1 \
    NUMBA_DISABLE_JIT=1

COPY --chown=$MAMBA_USER:$MAMBA_USER environment.yml /tmp/environment.yml
RUN micromamba env create -f /tmp/environment.yml && micromamba clean --all --yes

SHELL ["micromamba", "run", "-n", "ww-ci-39", "/bin/bash", "-c"]

USER root
RUN apt-get update && apt-get install -y --no-install-recommends g++ && rm -rf /var/lib/apt/lists/*
USER $MAMBA_USER

EXPOSE 8888
CMD jupyter lab --ip=0.0.0.0 --port=8888 --no-browser --NotebookApp.token='' --NotebookApp.password=''

