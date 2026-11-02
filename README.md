# OpenMeteo Fetch

OpenMeteo Fetch is a native Android app that lets you query the weather precisely when you need it, built entirely in Java.

- It pulls data directly from the [Open-Meteo API](https://open-meteo.com/).
- Users can toggle exactly which parameters are desired so no byte of mobile bandwidth is wasted.
- The location can be set through three flexible methods:
  - **Manual:** Enter coordinates manually. Ideal if you prefer to deny location permissions and want a "set-and-forget" configuration.
  - **Automatic:** Triggers a location permission prompt every time a query is made. Ideal if you travel frequently and always want real-time local updates.
  - **Hybrid:** If no manual location is set, the app queries system location services once and caches the coordinates for all subsequent weather lookups. Ideal for a quick setup in your general area.

## Credits

- All weather data courtesy of the [Open-Meteo API](https://open-meteo.com/) under the CC-BY-4.0 license.
- Weather icons courtesy of [weather-icons by Erik Flowers](https://github.com/erikflowers/weather-icons) under the SIL OFL 1.1 license.

## License

- This project is licensed under the [MIT LIcense](LICENSE).
