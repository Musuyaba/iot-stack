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
> Expected Output: Docker version 24.0.2, build cb74dfc
```bash
cpp --version 
```
> Expected Output: cpp (Rev7, Built by MSYS2 project) 13.1.0
- Nodejs (Opsional)
```bash
node -v
```
> Expected Output: v16.15.0
- Python (Opsional)
```bash
$ python --version
```
> Expected Output: Python 3.10.4

## Penggunaan
Cloning repo ini terlebih dahulu atau langsung clone repo stack yg dibutuhkan
```bash
$ git clone https://github.com/Musuyaba/iot-stack
$ cd iot-stack
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
/iot-stack$ cd mosquitto-stack
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
Tolong jangan segan untuk menghubungi saya melalui:
- [Website](https://musuyaba.my.id)
- <m.sulthon.yb@gmail.com>
- [Telegram @musuyaba](https://t.me/musuyaba)