FROM ubuntu
RUN apt update && apt install -y curl
WORKDIR /app
COPY arquivo.txt .
# COPY --chown=user:group --chmod=755 arquivo.txt .