FROM python:3.14.0rc1-alpine3.22
LABEL maintainer="mwgrunny@gmail.com"
ARG VERSION=0.10.0
RUN pip install zapcli==$VERSION

ENTRYPOINT [ "zap-cli" ]
