<!-- mosquitto-stack -->
<!-- TODO: Rapikan Readme.md -->
Mosquitto - SSL - Authentication
docker compose --profile mosquitto-stack up --build -d
docker compose logs -f mosquitto-sub
docker compose exec mosquitto-broker mosquitto_passwd -b /mosquitto/config/password.txt newUser newUser
docker restart mosquitto-broker
docker compose exec mosquitto-pub mosquitto_pub -h mosquitto-broker -t test -m "Hello World as admin" -u admin -P admin
docker compose exec mosquitto-pub mosquitto_pub -h mosquitto-broker -t test -m "Hello World as user" -u user -P user
docker compose exec mosquitto-pub mosquitto_pub -h mosquitto-broker -t test -m "Hello World as newUser" -u newUser -P newUser
docker compose exec mosquitto-broker mosquitto_passwd -D /mosquitto/config/password.txt user
docker restart mosquitto-broker
docker compose exec mosquitto-pub mosquitto_pub -h mosquitto-broker -t test -m "Hello World as user" -u user -P user
docker compose --profile mosquitto-stack down

RabbitMQ - Telegraf - InfluxDB Grafana
EMQX - Telegraf - InfluxDB Grafana

Kafka
# iot-stack
