# Hong Kong Highest-Temperature Market Forecast

- Market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-7-2026
- Supplied market check: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-5-2026 is past/stale for this run; the latest relevant active market found is Jun 7.
- Time checked: 2026-06-07 00:16 HKT
- Active market pricing: Polymarket's accessible odds table showed 30°C leading around 29%, followed by 29°C around 27%, 31°C around 25%, 28°C around 11%, 32°C around 9%, 33°C around 3%, 34°C or higher around 1%, and lower buckets mostly under 2%. Treat live executable quotes as controlling.
- Predicted outcome today: 30°C bucket for Jun 7. Base case official HKO-station maximum is about 30.0-30.8°C, with 29°C the main rain-cap downside and 31°C the main upside if midday showers break.
- Predicted outcome tomorrow: 29°C bucket for Jun 8. HKO's official max forecast is 29°C under cloudy, showery, squally-thundery weather; third-party city forecasts run warmer, so 30°C is the main upside risk.
- Confidence: medium. HKO is the settlement anchor and points directly to 30°C today / 29°C tomorrow, but the day is shower/thunderstorm-driven and non-HKO city forecasts are 1-3°C warmer.
- Recommendation: yes, but only as a small, price-sensitive lean on Jun 7 30°C Yes if available at or below about 35c. My fair range is roughly 36-42%; above the mid-30s, the edge fades and no strong bet is justified.

## Key Drivers

- Polymarket resolves the Jun 7 market against HKO's finalized Daily Extract, specifically "Absolute Daily Max (deg. C)", measured to one decimal place.
- HKO's local forecast updated 2026-06-06 22:45 HKT called for mainly cloudy conditions, occasional showers, a few squally thunderstorms, heavy showers at times, and temperatures of 25-30°C.
- HKO's 9-day forecast updated 2026-06-06 21:50 HKT gives Jun 7 a 30°C maximum, 25°C minimum, 80-95% relative humidity, southwest force 4 winds, and high significant-rain probability; Jun 8 is 29°C max / 26°C min with heavy showers at times.
- HKO regional readings at 2026-06-07 00:00 HKT showed the Hong Kong Observatory station at 26°C with 93% humidity, consistent with a humid, cloudy night rather than an early hot breakout.
- Timeanddate, WeatherBug, and AccuWeather run warmer for broader Hong Kong/Kowloon/Kwun Tong point forecasts, roughly 31-33°C for Jun 7, so the 31°C/32°C buckets remain live but receive less weight than HKO because they are not the resolution source.

## Risks To The Call

- Heavy or earlier daytime rainfall could cap the official HKO maximum in the 29°C bucket.
- A brighter late-morning or midday window before storms redevelop could lift the official station to 31.0°C or higher.
- Market prices are low-liquidity and moving quickly; the recommendation depends on actual executable prices, not stale displayed odds.

## Sources

- Polymarket Jun 7 market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-7-2026
- Polymarket Jun 5 market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-5-2026
- HKO current readings API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=rhrread&lang=en
- HKO local weather forecast API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=flw&lang=en
- HKO 9-day forecast API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=fnd&lang=en
- HKO Daily Extract resolution source: https://www.weather.gov.hk/en/cis/climat.htm
- Timeanddate Hong Kong 14-day forecast: https://www.timeanddate.com/weather/hong-kong/hong-kong/ext
- WeatherBug New Kowloon 10-day forecast: https://www.weatherbug.com/weather-forecast/10-day-weather/new-kowloon-hong-kong-ch
- AccuWeather Kwun Tong June forecast: https://www.accuweather.com/en/hk/kwun-tong/574/june-weather/574
