# acumagiao
buildx

```
docker buildx build --platform linux/amd64,linux/arm64 -t
```

build thường
```
sudo docker build -t acunetix_scan:25.1.250204093 .
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
docker run -d --name acunetix_scanner -p 3443:3443 acunetix_scan:25.1.250204093
```
import
```
podman -i acunetix_scan-25.1.250204093.tar
```
