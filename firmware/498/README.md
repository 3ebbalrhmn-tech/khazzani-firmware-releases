# ESP8266 OTA build 498 — USB bench test only

This signed image repairs installation-status reporting for both current and
legacy OTA bootloaders. It is for the single USB bench board
`WT-B2870BDECA20` until a full OTA install, MQTT reconnection, retained
`installed` status, settings preservation, and reset have passed.

No ultrasonic sensor or pump is connected to that board. Customer rollout
requires a separate integrated pilot with both components attached.
