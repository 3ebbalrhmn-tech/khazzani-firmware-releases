# ESP8266 OTA build 495 — USB bench test only

This signed image was tested on the single USB bench board `WT-B2870BDECA20`.
It **failed** and is **not approved for customer rollout**. The board received
and staged the first 6 KiB via HTTPS Range requests, then a subsequent request
timed out. The existing firmware remained intact and MQTT reconnected.
