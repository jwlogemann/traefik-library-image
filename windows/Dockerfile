FROM mcr.microsoft.com/windows/nanoserver:1809

COPY ./traefik.exe /traefik.exe
COPY ./netapi32.dll /windows/system32/netapi32.dll

EXPOSE 80
ENTRYPOINT ["/traefik"]

# Metadata
LABEL org.label-schema.vendor="Containous" \
      org.label-schema.url="https://traefik.io" \
      org.label-schema.name="Traefik" \
      org.label-schema.description="A modern reverse-proxy" \
      org.label-schema.version="v1.7.9" \
      org.label-schema.docker.schema-version="1.0"
