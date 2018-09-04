FROM jupyter/datascience-notebook

USER root

RUN apt-get update && \
    apt-get upgrade -y && \
    pip install --upgrade pip synapseclient

CMD bash
