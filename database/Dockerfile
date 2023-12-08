FROM mongo:latest
ENV MONGO_INITDB_DATABASE mymongodatabase
COPY init-script.js /docker-entrypoint-initdb.d/
CMD ["mongod"]
