# Build
```
docker build -t dizzzm/coding/devops/nodeappweb:v1 .
```
# Run
```
docker run -d -m="512m" --cpu-period=100000 --cpu-quota=50000 -p 80:80 dizzzm/coding/devops/nodeappweb:v1
```