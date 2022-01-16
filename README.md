# sonarqube-arm - Docker image for raspberry pi 4 or any arm based processor

## Build your own sonarqube image from Dockerifle

```
git clone https://github.com/SonarSource/docker-sonarqube.git

cd 9/community/

docker build -t sonarqube-custom .

docker run -d -p 9000:9000 sonarqube-custom

```

## Run with docker-compose

```bash
docker-compose -f sonarqube-compose.yml up -d
```

## Refrences:
- https://github.com/SonarSource/docker-sonarqube

## Motivation:
As there is no sonarqube docker image availabe for arm based processor. This will help anyone who wants to run sonarqube on raspberrypi 4, Apple M1, AWS graviton or any arm processor.
