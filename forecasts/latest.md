# Hong Kong Highest-Temperature Market Forecast

- Market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-6-2026
- Time checked: 2026-06-06 14:48 HKT
- Active market pricing: Jun 6 highest temperature: 30°C 92.5%, 31°C 5%, 32°C 1.1%, 33°C <1%, 34°C <1%, with other buckets effectively <1%. Volume about $111.1K.
- Forward market checked: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-7-2026, with 30°C about 29% / 31c ask, 31°C 25%, 29°C 24%, 32°C 16%, 33°C 4%, 34°C or higher 2%. Volume about $2.0K.
- Predicted outcome today: 30°C bucket for Jun 6. Base case is that the official HKO station has already peaked or is close to peak in the 30.0-30.9°C range; active showers and thunderstorms make a fresh 31°C+ late-day print less likely.
- Predicted outcome tomorrow: 30°C bucket for Jun 7, with 29°C and 31°C both live depending on rainfall timing and any sunny breaks. Base case official maximum is around 30.0-30.8°C.
- Confidence: medium for Jun 6, low-to-medium for Jun 7. Today's price and storm-cooled observations point strongly to 30°C, but I do not have the finalized intraday max yet. Tomorrow has clear source agreement near 30°C but high bucket risk from showers.
- Recommendation: No new bet on the current Jun 6 market. The likely 30°C outcome is already priced around 92.5c, leaving little compensation for final-data or late-day bucket risk. For Jun 7 only, there is a small watchlist lean toward Yes on 30°C around 31c or lower, but it is not a high-conviction trade.

## Key Drivers

- The provided Jun 5 market is now stale/post-event; Polymarket shows the 34°C outcome at 100% and related navigation points to Jun 6 and Jun 7 markets.
- HKO current observations at 14:00 HKT showed the Hong Kong Observatory station at 27°C with 88% humidity; Chek Lap Kok was the warmest listed station at 29°C.
- HKO reported lightning, showers developing around the Pearl River Estuary, heavier showers expected in parts of the territory, and a thunderstorm warning active until 15:30 HKT.
- HKO's local forecast says a broad trough is bringing showers and thunderstorms to the Guangdong coast, with mainly cloudy weather and heavier showers in some areas this afternoon and tonight.
- HKO's 9-day forecast for Jun 7 gives a 30°C maximum with mainly cloudy weather, occasional showers, heavier showers in some areas, and squally thunderstorms.
- Weather.com broadly agrees with the wet cap: Jun 6 high 31°C with heavy/torrential thunderstorms and Jun 7 high 30°C with thunderstorms. Timeanddate is warmer for the broader Hong Kong/HKIA area, but also shows overcast thunderstorms, so I treat it as an upside-risk source rather than the base case for the HKO station.

## Risks To The Call

- The official HKO intraday maximum may already have reached 31.0°C+ before the 14:00 observation, which would invalidate the Jun 6 30°C bucket call.
- Any late sunny break or lull in showers could still lift the official station by 1-2°C.
- For Jun 7, heavy morning or afternoon rain could cap the high in the 29°C bucket, while broken cloud and stronger southwest flow could push 31°C.
- Resolution uses HKO's finalized Absolute Daily Max at the Hong Kong Observatory station to one decimal place; hotter regional stations do not settle the market.

## Sources

- Polymarket Jun 6 market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-6-2026
- Polymarket Jun 7 market: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-7-2026
- HKO current weather report API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=rhrread&lang=en
- HKO local weather forecast API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=flw&lang=en
- HKO 9-day forecast API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=fnd&lang=en
- HKO daily maximum temperature data resource: https://data.gov.hk/en-data/dataset/hk-hko-rss-daily-temperature-info-hko/resource/fa0008a3-035f-4d5d-a342-81b1c858529f
- Weather.com 10-day forecast: https://weather.com/en-GB/weather/tenday/l/Hong%2BKong%2BPeople%27s%2BRepublic%2Bof%2BChina?placeId=3d0654fa7f86f5b20cb9cf9de12fd82013d721bacfe9b4a49cd3cc0160b8679e
- Timeanddate 14-day forecast: https://www.timeanddate.com/weather/hong-kong/hong-kong/ext
