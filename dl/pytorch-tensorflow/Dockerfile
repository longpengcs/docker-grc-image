FROM continuumio/miniconda3:4.8.2

RUN conda install pytorch torchvision cpuonly -c pytorch -y && \
  conda install tensorflow==1.14.0 -y && \
  conda clean --all
