# ESP8266 OTA build 498 — USB bench test only

This signed image **passed OTA installation** on the USB bench board
`WT-B2870BDECA20`: it booted build 498, reconnected to MQTT, and published
retained `installed` status. It then encountered an exception while the
laptop's test hotspot was unavailable. The exact-match diagnostic ELF decoded
the fault to the ESP8266 core's `WiFiServer::accept` / `setNoDelay` path.

Build 498 is **not approved for customer rollout**. Build 499 binds the setup
web server to the AP interface and does not service it with no AP clients.

No ultrasonic sensor or pump is connected to the bench board. Customer rollout
also requires a separate integrated pilot with both components attached.
