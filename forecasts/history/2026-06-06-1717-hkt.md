# Hong Kong Highest-Temperature Market Forecast

- Market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-6-2026
- Forward market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-7-2026
- Time checked: 2026-06-06 17:17 HKT
- Active market pricing: Jun 6 highest temperature: 30°C about 97.5-98% / Buy Yes 97.8c, 31°C about 3.4% / Buy Yes 3.8c, all higher buckets effectively below 1%. Volume about $140.5K.
- Forward market pricing: Jun 7 highest temperature: 30°C 27% / Buy Yes 27c, 31°C 26% / Buy Yes 26c, 29°C 21% / Buy Yes 22c, 32°C 17% / Buy Yes 17c, 28°C 11% / Buy Yes 11.9c, 33°C 3%, 34°C or higher 1%. Volume about $6.1K.
- Predicted outcome today: 30°C bucket for Jun 6. HKO's provisional regional maximum table shows the HK Observatory station at 30.4°C maximum since midnight as of 16:00 HKT; that sits in the 30.0-30.9°C bucket. The current-weather report shows the HKO station at 28°C at 16:00 HKT, with high humidity and unsettled weather, making a late move to 31.0°C+ unlikely.
- Predicted outcome tomorrow: 30°C bucket for Jun 7, with 29°C and 31°C as the nearest live alternatives. Base case official-station maximum is around 30.0-30.8°C.
- Confidence: high for today's 30°C bucket; medium for tomorrow. Today's call is anchored by the observed/provisional HKO station max and late-day cooling under showers. Tomorrow has meaningful one-bucket risk from shower timing and cloud breaks.
- Recommendation: no fresh bet on the Jun 6 market at current pricing; it looks broadly fair after the move to about 98%. For Jun 7, modest Yes lean on 30°C while it is near 27-30c, but size cautiously because 29°C/31°C remain plausible.

## Key Drivers

- The provided Jun 5 market is stale/post-event. The current relevant market is Jun 6, and the Jun 7 forward market is now active.
- Polymarket resolves these contracts against HKO's finalized "Absolute Daily Max (deg. C)" in the Daily Extract at one-decimal precision, so the HK Observatory station matters more than hotter regional stations.
- HKO's provisional since-midnight table at 16:00 HKT shows HK Observatory maximum at 30.4°C. Hotter regional maxima, such as Chek Lap Kok at 32.9°C and Sham Shui Po at 32.8°C, do not determine settlement.
- HKO's local forecast says a broad trough is bringing showers and thunderstorms to the Guangdong coast, with tonight/tomorrow mainly cloudy and occasional showers; tomorrow's range is 26-30°C.
- HKO's 9-day forecast for Jun 7 gives a 30°C maximum, mainly cloudy conditions, occasional showers, squally thunderstorms, heavier showers in some areas, and high probability of significant rain.
- Weather-Forecast's 1-3 day outlook is also rain-capped around a 30°C maximum, while WeatherBug's New Kowloon forecast is warmer around 90°F/32°C. I treat the warmer urban read as upside risk, not the settlement base, because it is not the official HKO station.

## Risks To The Call

- Today's provisional 30.4°C reading could be revised in the finalized HKO Daily Extract, though a revision across the 31.0°C threshold is not the base case.
- A short late sunny break before evening could still lift the official station into the 31°C bucket.
- For Jun 7, earlier/heavier rain could cap the official high in the 29°C bucket; broken cloud or warmer southwest flow could push 31°C.
- Resolution uses HKO's finalized official-station Absolute Daily Max to one decimal place. Broader Hong Kong, airport, and regional-station temperatures can differ materially.

## Sources

- Polymarket Jun 6 market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-6-2026
- Polymarket Jun 7 market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-7-2026
- HKO regional max/min since midnight CSV: https://data.weather.gov.hk/weatherAPI/hko_data/regional-weather/latest_since_midnight_maxmin.csv
- HKO current weather report API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=rhrread&lang=en
- HKO local weather forecast API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=flw&lang=en
- HKO 9-day forecast API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=fnd&lang=en
- HKO open data catalogue: https://www.hko.gov.hk/en/abouthko/opendata_intro.htm
- WeatherBug New Kowloon 10-day forecast: https://www.weatherbug.com/weather-forecast/10-day-weather/new-kowloon-hong-kong-ch
- Weather-Forecast Hong Kong forecast: https://www.weather-forecast.com/locations/Hong-Kong/forecasts/latest
