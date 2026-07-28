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

## Latest — v1.5.1

| File | SHA-256 |
|------|---------|
| `tjr_mini_v1.5.1-ota.bin` | `c0561c69ae7e7fdebc5bf1796e246f4df191d3e9b6fba6fe9b678b8b9d11effb` |
| `tjr_241_v1.5.1-ota.bin`  | `383ba88296fbb455f849c954be6558867f95227859e3aecb60a218bdbb511fad` |
