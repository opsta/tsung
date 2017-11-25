```
cd tsung
docker-compose up -d
docker exec tsung_tsung_1 tsung-recorder start
docker exec tsung_tsung_1 tsung-recorder stop
docker exec tsung_tsung_1 tsung -k start
docker exec tsung_tsung_1 tsung -k stop
```