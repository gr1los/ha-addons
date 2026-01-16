FROM ghcr.io/music-assistant/server:2.8.0b6

COPY ytmusic /app/venv/lib/python3.13/site-packages/

RUN set -x \
    && apt-get update \
    && apt-get install -y --no-install-recommends \
        curl \
        unzip \
    && curl -fsSL https://deno.land/install.sh | bash -s -- -y

