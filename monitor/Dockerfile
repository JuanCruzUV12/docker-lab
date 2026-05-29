FROM ubuntu:24.04

RUN apt-get update && \
    apt-get install -y \
    stress \
    stress-ng \
    htop \
    cpulimit \
    procps \
    psmisc \
    python3

WORKDIR /app

COPY script_cpu_ram.py .

CMD ["bash"]
