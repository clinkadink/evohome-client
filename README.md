

#EvoPi
==============================



![GitHub Logo](/images/evopi.png)

**EvoPi Instructions:**

From the terminal on the Raspeberry Pi run the following commands.

1. sudo mkdir EvoPi && cd EvoPi

2. sudo git clone https://github.com/clinkadink/evohome-client.git

3. cd evohome-client

4. sudo python evopi.py

Based on evohome-client

Build status: [![CircleCI](https://circleci.com/gh/watchforstock/evohome-client.svg?style=svg)](https://circleci.com/gh/watchforstock/evohome-client)

Python client to access the [Total Connect Comfort](https://international.mytotalconnectcomfort.com/Account/Login) RESTful API.

It provides support for **Evohome** and the **Round Thermostat**.  It supports only EU/EMEA-based systems, please use [somecomfort](https://github.com/kk7ds/somecomfort) for US-based systems.

This client uses the [requests](https://pypi.org/project/requests/) library. If you prefer an async-friendly client, [evohome-async](https://github.com/zxdavb/evohome-async) has been ported to use [aiohttp](https://pypi.org/project/aiohttp/) instead.

Documentation (in progress) at http://evohome-client.readthedocs.org/en/latest/

Provides Evohome support for Home Assistant (and other automation platforms), see http://home-assistant.io/components/evohome/
