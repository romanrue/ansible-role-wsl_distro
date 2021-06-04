FROM cytopia/docker-ansible:latest

RUN set -eux \
    && pip install --no-cache-dir --upgrade pip \
    && pip install --no-cache-dir \
        molecule[docker] \
    && :
