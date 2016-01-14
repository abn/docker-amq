# Docker: ActiveMQ

Yet another AMQ container; but this time its CentOS based!

```sh
docker run --it -p 8161:8161 alectolytic/amq
```

## Volumes
The following volumes can be mounted from the host.

| Volume  | Description |
| :------------ | :------------ |
| /opt/apache-activemq/conf | ActiveMQ configuration files. |
| /opt/apache-activemq/data | ActiveMQ data directory. |

## Ports
| Port  | Description |
| :------------ | :------------ |
| **8161** | AMQ HTTP port |
| **8162** | AMQ HTTPS port |
| **61616** | AMQ Openwire port |
| **1883** | AMQ MQTT port |
| **5672** | AMQ AMQP port |
| **61613** | AMQ STOMP port |
| **61617** | AMQ Openwire over SSL port |
| **8883** | AMQ MQTT over SSL port |
| **5671** | AMQ AMQP over SSL port |
| **61614** | AMQ STOMP over SSL port|