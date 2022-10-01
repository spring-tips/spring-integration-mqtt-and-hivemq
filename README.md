# Spring Integration MQTT & HiveMQ 

Hi, Spring fans! In this installment we look Spring Integration's support for MQTT and the HiveMQ broker. I'm joined by my friend and fellow Java Champion [Mary Grygleski (@mgrygles)](https://twitter.com/mgrygles)


* Spring Integration is an EAI framework 
* Spring Integration has had an MQTT adapter for closer to a decade 
* [HiveMQ - Enterprise ready MQTT to move your IoT data](https://www.hivemq.com/)
* [HiveMQ Introduction :: HiveMQ Documentation](https://www.hivemq.com/docs/hivemq/4.7/user-guide/introduction.html)
* [MQTT Support](https://docs.spring.io/spring-integration/reference/html/mqtt.html)
* [Home · mqtt/mqtt.org Wiki · GitHub](https://github.com/mqtt/mqtt.org/wiki) 
* Run it with `docker run -p 9090:8080 -p 1884:1883 hivemq/hivemq4 `
* [HiveMQ Control Center :: HiveMQ Documentation](https://www.hivemq.com/docs/hivemq/4.7/control-center/introduction.html) the default login for the console on :8080 is admin/hivemq 

## Update - 2022-09-30 

I've updated the code in a [new `aot` branch ](https://github.com/spring-tips/spring-integration-mqtt-and-hivemq/tree/aot) to use Spring Boot 3 and to work in the new AOT mode in Spring Framework 6 and Spring Boot 3. AOT replaces, and obviates the need for, Spring Native, as was shown in the video. 

