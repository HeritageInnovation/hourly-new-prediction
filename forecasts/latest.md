# Hong Kong Highest-Temperature Market Forecast

- Market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-6-2026
- Time checked: 2026-06-06 15:18 HKT
- Active market pricing: Jun 6 highest temperature: 30°C 93.1%, 31°C 7%, 32°C about 1.3-1.4%, 33°C <1%, 34°C <1%, with other buckets effectively <1%. Volume about $114.5K.
- Forward market checked: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-7-2026, with early pricing around 31°C 24%, 29°C 22%, 30°C 21%, 32°C 16%, 28°C 9%, 33°C 7%, and 34°C or higher 1%. Liquidity is still thin, roughly $1K-$2K.
- Predicted outcome today: 30°C bucket for Jun 6. Base case is that the official HKO station finishes in the 30.0-30.9°C range; at 15:00 HKT the HKO station was down to 27°C with showers and thunderstorm conditions, making a fresh 31°C+ late-day print less likely.
- Predicted outcome tomorrow: 30°C bucket for Jun 7, with 29°C and 31°C both live depending on shower timing and any sunny breaks. Base case official maximum is around 30.0-30.8°C.
- Confidence: medium. Today's setup is stronger than tomorrow's because late-day HKO observations and market pricing both point toward 30°C, but the official daily maximum is not finalized. Tomorrow has good HKO support for 30°C, but rain timing creates one-bucket risk either way.
- Recommendation: No new bet on the current Jun 6 market. The likely 30°C outcome is already priced around 93c, leaving little compensation for final-data or late-day bucket risk. For Jun 7, there is a small watchlist lean toward Yes on 30°C while it trades in the low-to-mid 20c range, but it is not a high-conviction trade yet.

## Key Drivers

- The provided Jun 5 market is stale/post-event; Polymarket navigation now points to the active Jun 6 and Jun 7 markets.
- Polymarket resolves these contracts against HKO's finalized "Absolute Daily Max (deg. C)" in the Daily Extract at one-decimal precision, so the Hong Kong Observatory station matters more than hotter regional stations.
- HKO current observations at 15:00 HKT showed the Hong Kong Observatory station at 27°C with 87% humidity; hotter listed regional stations were around 28-29°C.
- HKO's 14:45 local forecast says a broad trough is bringing showers and thunderstorms to the Guangdong coast, with mainly cloudy weather and heavier showers in some areas this afternoon and tonight.
- HKO's 13:15 9-day forecast for Jun 7 gives a 30°C maximum, mainly cloudy weather, occasional showers, heavier showers in some areas, and squally thunderstorms with high probability of significant rain.
- Weather-Forecast broadly agrees with a rain-capped setup near 30°C. Timeanddate and meteoblue are warmer for the broader Hong Kong/HKIA area, so I treat them as upside-risk inputs rather than the base case for the HKO station.

## Risks To The Call

- The official HKO intraday maximum may already have reached 31.0°C+ before the latest observation, which would invalidate the Jun 6 30°C bucket call.
- Any late sunny break or lull in showers could still lift the official station by about one bucket.
- For Jun 7, heavier or earlier rainfall could cap the high in the 29°C bucket, while broken cloud and stronger southwest flow could push 31°C.
- Resolution uses HKO's finalized Absolute Daily Max at the Hong Kong Observatory station to one decimal place; broader Hong Kong, airport, and regional-station temperatures can differ materially.

## Sources

- Polymarket Jun 6 market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-6-2026
- Polymarket Jun 7 market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-7-2026
- HKO current weather report API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=rhrread&lang=en
- HKO local weather forecast API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=flw&lang=en
- HKO 9-day forecast API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=fnd&lang=en
- HKO daily maximum temperature data resource: https://data.gov.hk/en-data/dataset/hk-hko-rss-daily-temperature-info-hko/resource/fa0008a3-035f-4d5d-a342-81b1c858529f
- Weather-Forecast Hong Kong forecast: https://www.weather-forecast.com/locations/Hong-Kong/forecasts/latest
- Timeanddate hourly forecast: https://www.timeanddate.com/weather/hong-kong/hong-kong/hourly
- Meteoblue Hong Kong forecast: https://www.meteoblue.com/en/weather/week/hong-kong_hong-kong_1819729
