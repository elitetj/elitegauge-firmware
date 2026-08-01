# Elite Gauge — Firmware

Public download host for Elite Gauge OTA firmware images.

These `-ota.bin` files are the over-the-air app images uploaded to the gauge
through its built-in WiFi updater (hold the value area 3s → join the gauge's
access point → open `http://192.168.4.1` → upload the `.bin` for your model).

| Model | File |
|-------|------|
| Elite Gauge Mini (1.64″) | `tjr_mini_v<ver>-ota.bin` |
| Elite Gauge 241 (2.41″)  | `tjr_241_v<ver>-ota.bin`  |

The website reads [`firmware.json`](https://elitegauge.com.au/firmware.json) to
surface the current version and download link. Update that manifest whenever a
new `.bin` is published here.

## Latest — v1.6

| File | SHA-256 |
|------|---------|
| `tjr_mini_v1.6-ota.bin` | `4803ed2c13e8e516b44bf44879ef8cdb51e31e092c7c4287f8be6c302af1648b` |
| `tjr_241_v1.6-ota.bin`  | `a7d249f88d1aeb66117b2d95a84fb2da48a43c3610d7e2285226648231b3adbd` |
