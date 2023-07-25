# IoT Stack by Musuyaba
Read this in other languages: [English](README.md), [Indonesia](README.id.md)

## Daftar Isi
* [About The Project](#about-the-project)
* [Persyaratan](#requirement)

## About The Project
Publik repo ini saya lampirkan sebagai portofolio saya sebagai IoT Engineer. Di repo ini ada beberapa *stack* yg sering saya gunakan dalam beberapa percobaan dan project. Di dalam masing-masing submodule terdapat terdapat cara penggunaan dalam README.md yg dapat dibaca untuk proyek *stack* tersebut. Harap gunakan repositori ini sebaik mungkin. Saran, kritikan, dan pertanyaan dapat menghubungi saya di [kontak](#contact). Terima kasih.

## Requirement
- Docker
```bash
docker -v
# Docker version 24.0.2, build cb74dfc
```
- CPP (Opsional)
```bash
cpp --version 
# cpp (Rev7, Built by MSYS2 project) 13.1.0
```
- Nodejs (Opsional)
```bash
node -v
# v16.15.0
```
- Python (Opsional)
```bash
python --version
# Python 3.10.4
```

## Penggunaan
```bash
# Cloning repo ini terlebih dahulu atau langsung clone repo stack yg dibutuhkan
git clone https://github.com/Musuyaba/iot-stack
cd iot-stack
```

## Features
### Mosquitto-Stack
- Authentication user-password
- Encryption password
- Add user
- Delete user
- Logging Mosquitto Broker
- Generate SSL Certificate
- Securing connection using OpenSSL
- Example on Cpp, Python, and Node.js

```bash
/iot-stack> cd mosquitto-stack
```

## Roadmap
### In Progress
- [ ] Work on Mosquitto-Stack
    - [x] Native
    - [ ] Cpp
    - [ ] Nodejs
    - [ ] Python

- [ ] Work on EMQX-Stack
- [ ] Work on RabbitMQ-Stack
- [ ] Work on Kafka-Stack
- [ ] Work on Socket-Stack
- [ ] Work on gGRPC-Stack

### Done ✓
- [x] Create Readme.md

## License

Distributed under the MIT License. 


## Contact
Please, if you had any hestitate contact me on: 
- [Website](https://musuyaba.my.id)
- <m.sulthon.yb@gmail.com>
- [Telegram @musuyaba](https://t.me/musuyaba)


<!-- # Mosquitto - Authentication
## docker compose --profile mosquitto-stack config
## docker compose --profile mosquitto-stack up --build -d
## docker compose logs -f mosquitto-sub
## docker compose exec mosquitto-broker mosquitto_passwd -b /mosquitto/config/password.txt newUser newUser
## docker restart mosquitto-broker
## docker compose exec mosquitto-pub mosquitto_pub -h mosquitto-broker -t topics/iot -m "Wellcome to Hell as admin" -u admin -P admin --cafile /mosquitto/certs/ca.crt --tls-version tlsv1.2 -d
## docker compose exec mosquitto-pub mosquitto_pub -h mosquitto-broker -t topics/iot -m "Wellcome to Hell as user" -u user -P user -d
## docker compose exec mosquitto-pub mosquitto_pub -h mosquitto-broker -t topics/iot -m "Wellcome to Hell as newUser" -u newUser -P newUser -d
## docker compose exec mosquitto-broker mosquitto_passwd -D /mosquitto/config/password.txt user
## docker restart mosquitto-broker
## docker compose exec mosquitto-pub mosquitto_pub -h mosquitto-broker -t topics/iot -m "Wellcome to Hell as user" -u user -P user
## docker compose --profile mosquitto-stack down

RabbitMQ - Telegraf - InfluxDB Grafana
EMQX - Telegraf - InfluxDB Grafana

Kafka
# iot-stack -->
