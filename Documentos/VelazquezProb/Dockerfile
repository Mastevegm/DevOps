FROM jupyter/datascience-notebook

USER root
RUN apt-get update && \
    apt-get install -y git wget &&\
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

RUN pip install qiskit

