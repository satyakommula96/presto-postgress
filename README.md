# Docker [PrestoDB](https://prestodb.io/)

## Build

```bash
docker build -t prestodb:latest --build-arg PRESTO_VERSION=<https://repo1.maven.org/maven2/com/facebook/presto/presto-server/> . 
```

## Run

```bash
docker run --name presto prestodb:latest
```
