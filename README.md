# DeepTick

Industrial-grade waterproof timers engineered for offshore research, marine operations, and subsea applications.

More at [deeptick.io](https://deeptick.io)

---

## Firmware Releases

## 1.0.3 (2026-01-17)

- Do not show current session in session history

### 1.0.2 (2026-01-16)

- Battery trend tracking: display shows charging/discharging rate (mV/min)
- Drain mode for battery testing (prevents sleep, keeps WiFi on)
- WiFi scans blocked during OTA to prevent interference
- WiFi timeout resets when client disconnects
- Web UI shows raw/calibrated/smoothed battery voltages

### 1.0.1 (2026-01-16)

- WiFi network scanner in MQTT Push section (scan button, dropdown selection)
- Battery drain test in diagnostics (continuous WiFi scanning for stress testing)
- Max TX power (19.5 dBm) for better signal through potting

### 1.0.0 (2026-01-16)

Initial release.
