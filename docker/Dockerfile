FROM ubuntu:22.04 AS builder

RUN apt-get update && apt-get install -y \
    python3 \
    python3-pip \
    python3.10-venv 

WORKDIR /opt
RUN git clone https://github.com/leehe228/POS-Data-Analyzer.git

WORKDIR /opt/POS-Data-Analyzer
RUN python3 -m venv venv

