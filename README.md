# Bookinfo Details Service

Details service has been developed on Ruby

## License

MIT License

## How to run with Docker

```bash
# Build Docker Image for details service
docker build -t details .

# Run details service on port 8081
docker run -d --name details -p 8081:8081 details\
  -e SERVICE_VERSION=v2 -e 'MONGO_DB_URL=mongodb://mongodb:27017/ratings' ratings
```

## How to run with Docker Compose

```bash
docker-compose up
```

## Website

[Opsta (Thailand) Co., Ltd.](https://www.opsta.co.th)