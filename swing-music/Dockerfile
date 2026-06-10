ARG BUILD_VERSION

FROM ghcr.io/swingmx/swingmusic:${BUILD_VERSION}

ENV SWINGMUSIC_PORT=1970

CMD ["poetry", "run", "python", "manage.py", "--host", "0.0.0.0", "--config", "/data"]
