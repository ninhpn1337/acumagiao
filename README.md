# acumagiao
buld

```
docker buildx build --platform linux/amd64,linux/arm64 -t
```

list images: 

```
docker images
```

Xóa: 
```
sudo docker rmi acunetix:25.1.250204093
```

Run: 

```
docker run -d \                                                                        
  --name acunetix_scanner \
  -p 3443:3443 \
  acunetix:25.1.250204093

```
