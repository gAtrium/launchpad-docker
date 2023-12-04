FROM evm-base
COPY run.sh /run.sh
RUN ["chmod", "+x", "/run.sh"]
RUN ["mkdir", "/app"]
WORKDIR /app

EXPOSE 3000

# Execute yarn and yarn start upon container startup
ENTRYPOINT ["/run.sh"]
