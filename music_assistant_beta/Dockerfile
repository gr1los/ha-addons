FROM ghcr.io/music-assistant/server:beta

RUN sed -i '229,230d' `find / -type f -wholename '*ytmusic/__init__.py' 2>/dev/null`