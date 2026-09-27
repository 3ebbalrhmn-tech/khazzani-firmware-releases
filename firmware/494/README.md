# ESP8266 OTA build 494 — bench diagnostic only

This signed image was tested on the single USB bench board `WT-B2870BDECA20`.
It **failed** and is **not approved for customer rollout**. The smaller TLS buffer
connected to GitHub, but GitHub did not negotiate a matching maximum fragment
length; the full-file transfer timed out before completing. The original
firmware remained intact, and the device reconnected to MQTT.

Do not send this release to production devices until a full physical update and
post-update connectivity check have passed.
