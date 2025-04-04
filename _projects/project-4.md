---
title: "MQTT Fleet Control"
excerpt: "A Remote Procedure Call and System Monitoring Platform based on MQTT<br/><img src='/images/mqttfc_dashboard.png'>"
collection: Projects
---

MQTTFC is a tailor-made remote function call (RFC) infrastructure I designed and developed at the C2E lab. This lightweight RFC infrastructure simply binds clients' remotely executable functions to MQTT topics. Thus, any remote client can publish to the function topic and pass the arguments within the message payload, and the function will be called in the client system which has the corresponding function and has subscribed to the topic of that function. 