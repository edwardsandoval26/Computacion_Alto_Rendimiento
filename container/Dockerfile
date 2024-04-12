FROM ubuntu:22.04

# Install open-mpi
RUN apt-get update 
RUN apt install -y build-essential
RUN apt-get install -y openmpi-bin libopenmpi-dev
RUN export OMPI_ALLOW_RUN_AS_ROOT=1
RUN export OMPI_ALLOW_RUN_AS_ROOT_CONFIRM=1
