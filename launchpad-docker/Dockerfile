FROM evm-base

WORKDIR /app

EXPOSE 3000

# Execute yarn and yarn start upon container startup
ENTRYPOINT ["yarn", "install", && "yarn", "start"]
