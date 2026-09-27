# ESP8266 OTA build 497 — USB bench test only

This signed image **passed the USB bench OTA installation** on
`WT-B2870BDECA20`. Two timed-out Range requests retried successfully; the
board booted build 497 and reconnected to MQTT. However, its retained OTA
result remained `downloading` because the earlier build 496 did not save the
target-build field. Build 498 adds a backward-compatible status migration.

No ultrasonic sensor or pump is connected to that board. Build 497 is **not
approved for customer rollout** without a separate integrated pilot.
