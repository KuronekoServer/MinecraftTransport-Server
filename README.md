[![GitHub issues](https://img.shields.io/github/issues/kuronekoserver/MinecraftTransport-Server?style=for-the-badge)](https://github.com/kuronekoserver/MinecraftTransport-Server/issues)
[![GitHub stars](https://img.shields.io/github/stars/kuronekoserver/MinecraftTransport-Server?style=for-the-badge)](https://github.com/kuronekoserver/MinecraftTransport-Server/stargazers)
[![GitHub license](https://img.shields.io/github/license/kuronekoserver/MinecraftTransport-Server?style=for-the-badge)](https://github.com/kuronekoserver/MinecraftTransport-Server)
# MinecraftTransport-Server
MinecraftTransport-Client用のサーバーソフトです。
https://github.com/KuronekoServer/MinecraftTransport-Client
# How to Use
java -jar server.jar

# Configuration file
mctp.kuroneko6423.comとしてmctp.jsonを作成した例
```
{
  "listen_host": "0.0.0.0",
  "listen_port": 9998,
  "host": "mctp.minecraft.com",
  "port_start": 40000,
  "port_range": 10000,
  "enable_prometheus_metrics": true,
  "prometheus_metrics_host": "0.0.0.0",
  "prometheus_metrics_port": 9997
}
```

# WARNING
必ず最新版をご使用ください

# Support
[![Discord Banner 4](https://discordapp.com/api/guilds/867038364552396860/widget.png?style=banner4)](https://discord.gg/Y6w5Jv3EAR)

  
