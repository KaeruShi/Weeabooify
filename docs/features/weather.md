# Weather

Weeabooify includes an integrated weather feature that surfaces current conditions directly on your lockscreen and quick settings.

## Auto Update

Enable automatic background weather data refresh so your lockscreen always shows current conditions without manual intervention.

## Update Interval

Configure how frequently the weather data refreshes. More frequent updates keep conditions current but use more battery.

## Update Status

View the last successful update time and fetch status, so you can tell if weather data is stale or if a network issue occurred.

## Units

Switch between:

- **Metric** (°C, km/h, mm)
- **Imperial** (°F, mph, in)

## Icon Pack

Weeabooify provides a customizable icon pack for weather conditions.
- Default
- Google

::: info
Will add more icon packs in the future.
:::

## Provider

Choose your preferred weather data provider. Weeabooify uses [Open-Meteo](https://open-meteo.com/) by default for free, no-API-key weather data, with reverse geocoding via Nominatim.

::: info
Weather updates run via **WorkManager** periodic tasks, so they continue even when the Weeabooify app is not in the foreground. Air quality data is fetched in parallel alongside current conditions.
:::
