# ESP8266 OTA build 496 — USB bench test only

This signed image **passed the USB bench OTA test** on `WT-B2870BDECA20`:
the full file downloaded, its RSA signature verified, the board booted build
496, reconnected to MQTT, and retained its identity and saved settings after
a reset. The bench board had no ultrasonic sensor or pump attached, so this
image is **not yet approved for customer rollout** without an integrated pilot.
