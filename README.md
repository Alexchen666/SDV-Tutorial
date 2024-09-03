# SDV-Tutorial

This tutorial demonstrates the use of two powerful tools in the field of synthetic data: [SDV (Synthetic Data Vault)](https://github.com/sdv-dev/SDV) and [Anonymeter](https://github.com/statice/anonymeter). The focus is on generating and evaluating synthetic data with SDV, followed by assessing the privacy risks of the generated data using Anonymeter.

Key points covered:

1. Generation of synthetic data using SDV's single-table methods
2. Evaluation of the quality and utility of the synthetic data
3. Analysis of potential privacy risks in the synthetic data using Anonymeter

For demonstration purposes, the tutorial uses a custom-generated fake dataset. This approach allows for a controlled environment to showcase the capabilities of both tools.

The tutorial is written in Traditional Chinese, making it accessible to Chinese-speaking data scientists, researchers, and privacy professionals.

The tutorial environment can be obtained on [DockerHub](https://hub.docker.com/r/alexcnics/sdv.tutorial) by pulling images, executing and mounting files `docker run -p 8888:8888 -v {TUTORIAL_FILE_PATH}:/home/jovyan alexcnics/sdv.tutorial:{TAG}`, or can be built from the Dockerfile in `Env`. Besides, you can install all required packages in `Env/requirements.txt` in Python 3.10 environment.
