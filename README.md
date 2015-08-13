# Docker sonar image with cxx plugin

## Build
```bash
docker build -t sonar .
```

## Run
```bash
docker run -it --name sonar -p 9000:9000 -p 9092:9092 sonar
```
