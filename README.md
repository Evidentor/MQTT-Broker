# Devices-Service

## About
The MQTT Mosquitto Broker is a lightweight, high-performance message
broker that facilitates communication between IoT devices and backend
services using the MQTT protocol. It efficiently handles telemetry data
and commands, enabling reliable, real-time messaging across the system.

## System Requirements
- Docker

## Configuration
Check `/mosquitto/mosquitto.conf` file.

## How to Install?

### 1. Clone the repository
```shell
git clone https://github.com/Evidentor/Devices-Service.git
cd Devices-Service
```

## How to Run?
#### 1. Start the docker container
```shell
docker compose up -d
```

#### 2. Stop the docker container
```shell
docker compose down
```
