# ESP8266 OTA build 499 — USB bench test only

This signed image isolates the setup HTTP server on `192.168.4.1` and skips
HTTP/DNS polling when no phone is connected to the board AP. It addresses the
`WiFiServer::accept` crash observed on build 498 during hotspot instability.

The image is not approved for customer rollout until an OTA install, offline
hotspot stress, reconnection, and integrated sensor/pump pilot have passed.
