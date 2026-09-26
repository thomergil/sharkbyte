# SharkByte

Industrial-grade waterproof timers engineered for offshore research, marine operations, and subsea applications.

More at [sharkbyte.watch](https://sharkbyte.watch)

---

## Firmware Releases

### 1.0.6 (2026-09-26)

- Battery trend shows "+" within seconds of connecting the charger
- Battery trend shows a drain as soon as it stands out from noise
- Battery readings average more samples for less noise
- Web diagnostics show battery trend direction and noise

### 1.0.5 (2026-09-24) — do not use

- **Do not use.** Battery trend shows 0.0 almost all the time. Use 1.0.6
- Battery trend no longer shows a false "+" after WiFi turns off
- Battery trend is a fit over 10 minutes; shows 0.0 until ready
- Battery percentage, voltage and trend use the same reading
- Web firmware upload asks for a code shown on the display
- Failed firmware start rolls back to the previous firmware
- Saved WiFi and MQTT passwords no longer sent to the web page
- MQTT push fixed for longer messages; sends newest battery log
- Device ID limited so the WiFi name fits
- Clock stops at 99:59 instead of wrapping at 100 hours
- Let the display settle at boot so the splash screen shows
- `make usb` keeps calibration and other saved data
- `make test` runs host-side unit tests

### 1.0.4 (2026-01-19)

- Rename to SharkByte

### 1.0.3 (2026-01-17)

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
