# Start from a core stack version
FROM quay.io/jupyter/base-notebook:latest
# Install in the default python3 environment
RUN pip install --quiet --no-cache-dir sdv==1.10 anonymeter==1.0.0 seaborn && \
    fix-permissions "${CONDA_DIR}" && \
    fix-permissions "/home/${NB_USER}"