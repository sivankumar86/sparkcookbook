## how to build and push to jfrog repo 


docker build -t sbt-alpine:1.5_2.12 .
docker tag sbt-alpine:1.5_2.12 domain-docker.jfrog.io/sbt-alpine:1.5_2.12
docker push domain-docker.jfrog.io/sbt-alpine:1.5_2.12
