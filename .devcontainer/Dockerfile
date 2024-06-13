FROM pytorch/pytorch:1.13.1-cuda11.6-cudnn8-runtime

# Install additional packages
RUN apt-get update && apt-get install -y g++

# setup for conda
RUN conda init bash
RUN echo "conda activate gaussian_splatting" >> ~/.bashrc