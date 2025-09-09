FROM mcr.microsoft.com/devcontainers/python:1-3
COPY corporate.crt /usr/local/share/ca-certificates
RUN chmod 644 /usr/local/share/ca-certificates/corporate.crt && update-ca-certificates
ENV NODE_EXTRA_CA_CERTS=/usr/local/share/ca-certificates/corporate.crt