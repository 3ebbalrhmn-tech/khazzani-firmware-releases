# ESP8266 OTA build 497 — USB bench test only

This signed image adds a retained `installed` result after the new firmware
boots and reconnects to MQTT. It uses the bounded HTTPS Range downloader that
passed the build 496 USB bench test. Build 497 is for the single USB bench
board `WT-B2870BDECA20` until installation and status reporting pass.

No ultrasonic sensor or pump is connected to that board. Customer rollout
requires a separate integrated pilot with both components attached.
