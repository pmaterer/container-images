FROM debian:bullseye

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
    python3-pip \
    && rm -rf /var/lib/apt/lists/* \
    && rm -Rf /usr/share/doc \
    && rm -Rf /usr/share/man \
    && apt-get clean

RUN pip3 install --upgrade --no-cache-dir pip