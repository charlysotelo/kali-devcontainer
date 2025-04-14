FROM kalilinux/kali-rolling:latest

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update && \
  apt-get install -y \
  gobuster \
  nmap \
  curl \
  git \
  seclists \
  tmux \
  && apt-get autoremove -y \
  && apt-get autoclean -y \
  && rm -rf /var/lib/apt/lists/*

