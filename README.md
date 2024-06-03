# Apache Proxy Server
---
## How to build
Clone the files
```bash
$ git clone https://github.com/MT-Kohei-Yamada/apache_proxy.git
```
Docker container start
```bash
$ cd apache_proxy
$ docker compose up -d
```
Proxy server starts on 8080 port
### Environment
Create .env file (Rename .env.example file to .env file)
> PROXY_PORT=8081 # Default port is 8080

&emsp;0.0.0.0:8081->80/tcp # Listen 8081