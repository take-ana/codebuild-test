FROM node:26.7.0-alpine3.24

VOLUME ["/data"]
COPY ./src/ /data/src/
RUN chmod -R +x /data/src/
ENTRYPOINT [ "node", "/data/src/server.js" ]
