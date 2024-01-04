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
```
> Expected Output: 
>>Docker version 24.0.2, build cb74dfc
```bash
cpp --version 
```
> Expected Output: 
>> cpp (Rev7, Built by MSYS2 project) 13.1.0
- Nodejs (Opsional)
```bash
node -v
```
> Expected Output: 
>>v16.15.0
- Python (Opsional)
```bash
$ python --version
```
> Expected Output: 
>>Python 3.10.4

## Penggunaan
Cloning repo ini terlebih dahulu atau langsung clone repo stack yg dibutuhkan
```bash
$ git clone https://github.com/Musuyaba/iot-stack
$ cd iot-stack
```

## Features
### Mosquitto Stack
Mosquitto adalah salah product yg menggunakan MQTT Protocol. Penggunaan yg mudah dan ringan menjadikan mosquitto sangat sering digunakan.
- Authentication user-password
- Encryption password
- Add user
- Delete user
- Logging Mosquitto Broker
- Generate SSL Certificate
- Securing connection using OpenSSL
- Example on Python

```bash
/iot-stack$ cd mosquitto-stack
```

## Roadmap
### In Progress
- [ ] Work on Mosquitto Stack
    - [x] Native
    - [ ] Python
- [ ] Work on API Gateway - MySQL Stack
- [ ] Work on CoAP Stack
- [ ] Work on Webhook - MySQL - Grafana Stack
- [ ] Work on Webocket - MongoDB - Grafana Stack
- [ ] Work on EMQX - InfluxDB - Telegraf Stack
- [ ] Work on RabbitMQ - CrateDB - Grafana Stack
- [ ] Work on Kafka Stack
- [ ] Work on Redis - Elasticsearch - Kibana Stack
- [ ] Work on gGRPC - CassandraDB - Grafana Stack

### Done ✓
- [x] Create Readme.md

## License

Distributed under the MIT License. 


## Contact
Tolong jangan segan untuk menghubungi saya melalui:
- [Telegram @musuyaba](https://t.me/musuyaba)
- [Website](https://musuyaba.my.id) <sup><sub><sup><sub>Maaf, hosting murah 🙏</sub></sup></sub></sup>