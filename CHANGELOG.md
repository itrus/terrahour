# Changelog

## 1.0.0 (2026-10)

First web release, ported from [terrahour](https://github.com/ACoci86/terrahour) (Python, terminal).

### Ported
- World map with day/night shading, time-zone colouring, zoom and pan
- Per-city 24-hour timelines with working hours, overlap row and time scrubbing
- Go to time, home city, DST radar, stock-exchange view, alerts, weather
- Themes, 12/24-hour clock, compact layout, ambient view
- Built-in city list (about 12,000 cities) and land mask

### Added
- Mouse and touch support; responsive layout for phones
- Day/night strip under every timeline bar, with civil, nautical and astronomical twilight
- Shared daylight in the overlap row
- Weekends: city working hours skip weekends, with country-specific weekend days (Fri–Sat, Thu–Fri and others)
- Moon phase, illumination, moonrise and moonset; moon marker on the map
- Sun and moon altitude and azimuth for the selected city
- Daily change in day length

### Changed
- Settings are stored in the browser instead of a config file
- Alerts use browser notifications and a short beep
