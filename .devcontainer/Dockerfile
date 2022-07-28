FROM continuumio/miniconda3:latest
COPY environment.yml ${HOME}/environment.yml
COPY postBuild ${HOME}/postBuild
RUN conda env create -f ${HOME}/environment.yml
RUN bash ${HOME}/postBuild
