FROM quay.io/jupyter/pytorch-notebook:cuda12-python-3.11.8

USER root
# Add the 'users' group if it doesn't already exist, then add jovyan to it
RUN groupadd -f users \
    && usermod -a -G users jovyan

USER jovyan
