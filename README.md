
![CasaOS HomeAutomation AppStore](./banner.png)

# CasaOS HomeAutomation AppStore

A CasaOS custom Appstore containing some additional images needed to make your home smart.


## Supporting/Sponsoring this project

You like the project and you want to support me?

[<img src="https://github.md0.eu/uploads/donate-button.svg" height="50">](https://www.paypal.com/donate/?hosted_button_id=3NEVZBDM5KABW)


## 📃 Table of Contents

> ⚠ The information below is updated for **v0.4.4**.

- [Introduction](#-introduction)
- [Installation](#-installation)
- [List of Applications](#-list-of-applications)
- [Frequently Asked Questions / FAQs](#-frequently-asked-questions)
    - [How to Upgrade CasaOS](#-how-to-upgrade-casaos)
- [Contributing](#contributing)


## 🔥 Introduction

The **HomeAutomation AppStore** is a custom appstore built to work for [CasaOS](https://github.com/IceWhaleTech/CasaOS).

This custom appstore for CasaOS contains some additional configurations of docker images.


### 💎 CasaOS HomeAutomation Appstore URL

```bash
https://github.com/mr-manuel/CasaOS-HomeAutomation-AppStore/archive/refs/tags/latest.zip
```


## ✅ Installation

- Go to your CasaOS dashboard.

  ![Step 1](./tip-1.jpg)

- Open the appstore and click `Add Source` button  located on the right just above the apps list.

  ![Step 2](./tip-2.jpg)

- Paste the appstore link
  ```
  https://github.com/mr-manuel/CasaOS-HomeAutomation-AppStore/archive/refs/tags/latest.zip
  ```
  and then click `Add` to submit.

  ![Step 3](./tip-3.jpg)

- Wait for the installation to finish. Done!

> **NOTE: Custom Appstore is only supported on CasaOS version [0.4.4](https://blog.casaos.io/blog/32.html) and above. How to upgrade? [Click here](#-how-to-upgrade-casaos)**


## 🛠 List of Applications

| # | Application  | Version | Description |
| :---: | :---: | --- | --- |
| 1 | <img src="https://raw.githubusercontent.com/mr-manuel/CasaOS-HomeAutomation-AppStore/latest/Apps/Frigate/icon.png" width="32"/><br>[Frigate NVR](https://frigate.video) | 0.12.1 | A complete and local NVR designed for Home Assistant with AI object detection. Uses OpenCV and Tensorflow to perform realtime object detection locally for IP cameras. |
| 2 | <img src="https://raw.githubusercontent.com/mr-manuel/CasaOS-HomeAutomation-AppStore/latest/Apps/InfluxDB/icon.png" width="32"/><br>[InfluxDB](https://www.influxdata.com/influxdb/) | latest | Manage all types of time series data in a single, purpose-built database. |
| 3 | <img src="https://raw.githubusercontent.com/mr-manuel/CasaOS-HomeAutomation-AppStore/latest/Apps/InfluxDB-v1/icon.png" width="32"/><br>[InfluxDB v1](https://www.influxdata.com/influxdb/) | 1.8.10 | Manage all types of time series data in a single, purpose-built database. |
| 4 | <img src="https://raw.githubusercontent.com/mr-manuel/CasaOS-HomeAutomation-AppStore/latest/Apps/InfluxDB-v2/icon.png" width="32"/><br>[InfluxDB v2](https://www.influxdata.com/influxdb/) | 2.7.1 | Manage all types of time series data in a single, purpose-built database. |
| 5 | <img src="https://raw.githubusercontent.com/mr-manuel/CasaOS-HomeAutomation-AppStore/latest/Apps/Mosquitto/icon.png" width="32"/><br>[Mosquitto](https://mosquitto.org) | 2.0.16 | Eclipse Mosquitto is an open source (EPL/EDL licensed) message broker that implements the MQTT protocol versions 5.0, 3.1.1 and 3.1. Mosquitto is lightweight and is suitable for use on all devices from low power single board computers to full servers. |
| 6 | <img src="https://raw.githubusercontent.com/mr-manuel/CasaOS-HomeAutomation-AppStore/latest/Apps/Portainer-Agent/icon.png" width="32"/><br>[Portainer Agent](https://docs.portainer.io/admin/environments/add/docker/agent) | 2.18.4 | The Portainer Agent container is used by Portainer to communicate with the Portainer Server instance and provide access to the node's resources. |
| 7 | <img src="https://raw.githubusercontent.com/mr-manuel/CasaOS-HomeAutomation-AppStore/latest/Apps/Traefik/icon.png" width="32"/><br>[Traefik](https://traefik.io) | latest | Traefik is the leading open-source reverse proxy and load balancer for HTTP and TCP-based applications that is easy, dynamic and full-featured. |
| 8 | <img src="https://raw.githubusercontent.com/mr-manuel/CasaOS-HomeAutomation-AppStore/latest/Apps/Traefik-v1/icon.png" width="32"/><br>[Traefik v1](https://traefik.io) | 1.7 | Traefik is the leading open-source reverse proxy and load balancer for HTTP and TCP-based applications that is easy, dynamic and full-featured. |
| 9 | <img src="https://raw.githubusercontent.com/mr-manuel/CasaOS-HomeAutomation-AppStore/latest/Apps/Traefik-v2/icon.png" width="32"/><br>[Traefik v2](https://traefik.io) | 2.10 | Traefik is the leading open-source reverse proxy and load balancer for HTTP and TCP-based applications that is easy, dynamic and full-featured. |
| 10 | <img src="https://raw.githubusercontent.com/mr-manuel/CasaOS-HomeAutomation-AppStore/latest/Apps/Traefik-v3/icon.png" width="32"/><br>[Traefik v3](https://traefik.io) | 3.0 | Traefik is the leading open-source reverse proxy and load balancer for HTTP and TCP-based applications that is easy, dynamic and full-featured. |


## 💡 Frequently Asked Questions

### 👉 How to Upgrade CasaOS

Run the following command:

```bash
curl -fsSL https://get.casaos.io/update/v0.4.4 | sudo bash
```
