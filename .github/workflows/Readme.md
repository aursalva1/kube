# REST Product-Service
```
Construye la imagen Docker:

```
docker build -t product-service .
```
Ejecuta el contenedor Docker:
```
docker run -d --name product-service -p 3000:3000 --env-file .env product-service
```

## Uso de la API

1. Test Health

URL: http://192.168.10.26:3000/api/health
Método: get
Body: JSON (raw)


docker build . -t 192.168.10.26:32000/product-service:latest
docker tag product-service 192.168.10.26:32000/product-service:latest
docker push 192.168.10.26:32000/product-service:latest

http://192.168.10.26:32000/v2/_catalog


