An easy way to start and interate on the env is with:

```
docker-compose down -v; mvn clean package && docker-compose up --build
```

The system is pre-populated with a user`casuser`/`Mellon`. The QR Code for the user is in docs.