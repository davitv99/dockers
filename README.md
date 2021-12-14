# dockers

docker login registry.gitlab.com

docker build -t registry.gitlab.com/armdev/dockers .

docker push registry.gitlab.com/armdev/dockers

cd dockers

docker build -t registry.gitlab.com/armdev/dockers/openjdk11 openjdk11

docker push registry.gitlab.com/armdev/dockers/openjdk11

docker build -t registry.gitlab.com/armdev/dockers/openjdk12 openjdk12

docker push registry.gitlab.com/armdev/dockers/openjdk12

docker build -t registry.gitlab.com/armdev/dockers/openjdk13 openjdk13

docker push registry.gitlab.com/armdev/dockers/openjdk13

docker build -t registry.gitlab.com/armdev/dockers/openjdk14 openjdk14

docker push registry.gitlab.com/armdev/dockers/openjdk14

docker build -t registry.gitlab.com/armdev/dockers/openjdk15 openjdk15

docker push registry.gitlab.com/armdev/dockers/openjdk15

docker build -t registry.gitlab.com/armdev/dockers/openjdk16 openjdk16

docker push registry.gitlab.com/armdev/dockers/openjdk16

docker build -t registry.gitlab.com/armdev/dockers/openjdk17 openjdk17

docker push registry.gitlab.com/armdev/dockers/openjdk17

docker build -t registry.gitlab.com/armdev/dockers/mongodb mongodb

docker push registry.gitlab.com/armdev/dockers/mongodb

docker build -t registry.gitlab.com/armdev/dockers/redis redis

docker push registry.gitlab.com/armdev/dockers/redis

docker build -t registry.gitlab.com/armdev/dockers/postgres postgres

docker push registry.gitlab.com/armdev/dockers/postgres

docker build -t registry.gitlab.com/armdev/dockers/pgadmin pgadmin

docker push registry.gitlab.com/armdev/dockers/pgadmin

docker build -t registry.gitlab.com/armdev/dockers/postgis postgis

docker push registry.gitlab.com/armdev/dockers/postgis

docker build -t registry.gitlab.com/armdev/dockers/tomeeplume tomeeplume

docker push registry.gitlab.com/armdev/dockers/tomeeplume

docker build -t registry.gitlab.com/armdev/dockers/plume:8.0.4 plume8.0.4

docker push registry.gitlab.com/armdev/dockers/plume:8.0.4

docker build -t registry.gitlab.com/armdev/dockers/plume:8.0.8 plume8.0.8

docker push registry.gitlab.com/armdev/dockers/plume:8.0.8

docker build -t registry.gitlab.com/armdev/dockers/cassandra3.11.4 cassandra:3.11.4

docker push registry.gitlab.com/armdev/dockers/cassandra3.11.4

docker build -t registry.gitlab.com/armdev/dockers/cassandra4 cassandra4

docker push registry.gitlab.com/armdev/dockers/cassandra4

docker build -t registry.gitlab.com/armdev/dockers/zipkin zipkin

docker push registry.gitlab.com/armdev/dockers/zipkin

docker build -t registry.gitlab.com/armdev/dockers/rabbitmq rabbitmq

docker push registry.gitlab.com/armdev/dockers/rabbitmq

docker build -t registry.gitlab.com/armdev/dockers/cassandraweb cassandraweb

docker push registry.gitlab.com/armdev/dockers/cassandraweb

docker build -t registry.gitlab.com/armdev/dockers/pulsar pulsar

docker push registry.gitlab.com/armdev/dockers/pulsar

docker build -t registry.gitlab.com/armdev/dockers/pulsardashboard pulsardashboard

docker push registry.gitlab.com/armdev/dockers/pulsardashboard

docker build -t registry.gitlab.com/armdev/dockers/mongoadmin mongoadmin

docker push registry.gitlab.com/armdev/dockers/mongoadmin


