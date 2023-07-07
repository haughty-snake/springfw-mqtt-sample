# springfw-mqtt-sample

## mqtt client
```
https://mqttx.app/features
```

## mqtt broker
```
docker run -d  \
-p 1883:1883 -p 9001:9001 \
--restart always \
--name mosquitto \
csh0034/mosquitto
```
### 참고: https://velog.io/@csh0034/Spring-Integration-MQTT-%EC%97%B0%EB%8F%99

## spring boot + mqtt example
```
# gradle 기준 주요 라이브러리
implementation 'org.springframework.boot:spring-boot-starter-integration'
implementation 'org.springframework.integration:spring-integration-mqtt'
```
