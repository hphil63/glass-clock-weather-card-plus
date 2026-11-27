# Changelog

## 1.1.2

- Added optional `pressure_entity` chip with automatic 3-hour barometric trend arrow (rising / steady / falling).
- Tapping the pressure chip opens a liquid-glass 7-day pressure history chart directly inside the card (with 7-day min/max and 3-hour tendency).

## 1.1.1

- Added optional `indoor_humidity_entity` (shown next to the indoor label, e.g. `Innen · 48%`).

## 1.1.0

- Forked as **Glass Clock Weather Card Plus** (`custom:glass-clock-weather-card-plus`) so it can be installed side-by-side with the original card in HACS.
- Added a compact **today day-parts forecast row** above the clock (`Morgens` / `Mittags` / `Abends` / `Nachts`) using hourly forecasts (or Met.no), showing animated weather icons and high/low temperatures (`show_today_forecast`).
- Added optional detailed day-part metrics (`today_forecast_details`): condition text, rain probability/amount, wind direction arrow + speed, feels-like temperature, humidity, and air pressure.
- Added **fullscreen / panel-view mode** (`fullscreen: true`) to fill wall-tablet displays edge-to-edge without scrollbars.
- Added full German translations for the visual editor and weather conditions.

## 1.0.2

- The forecast comes back by itself after Home Assistant restarts: the subscription retries when the weather integration is not ready yet and subscribes again after a reconnection.

## 1.0.1

- README: how to avoid the browser cache when updating a manual installation.

## 1.0.0

First release.

- Big clock that fills the free space, with date, greeting and seconds bar (24 or 12 hours).
- Animated weather icons, current conditions, today's high and low, humidity and wind.
- Weather from a Home Assistant weather entity or from Met.no for a place picked on a map.
- Optional completion of missing forecast days with Met.no.
- Outdoor temperature and humidity sensors, indoor temperature next to the outdoor one.
- Up to 7 forecast days, showing only the days that fit.
- Calendar chips for today and tomorrow with types (label, icon, color) and waste collection examples.
- Dark, light and automatic style, custom colors, glow, corner radius, fonts and text size.
- Standard tap, hold and double tap actions.
- Visual editor for every option. Translations: English, Italian, German, French, Spanish, Dutch.
