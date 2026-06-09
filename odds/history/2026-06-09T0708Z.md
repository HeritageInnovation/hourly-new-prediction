# Odds Market Snapshot

## Time checked

2026-06-09 07:08 UTC / 2026-06-09 15:08 HKT.

Scheduled run invoked at 2026-06-09 15:07 HKT. No real trades, bets, wallet actions, order submissions, or execution integrations were used.

## Markets monitored

- Polymarket station-resolved highest-temperature markets for June 9, 2026: Hong Kong Observatory, Houston KHOU, NYC KLGA, Atlanta KATL, Chicago KORD, London EGLC, and Miami KMIA.
- Existing June 9 paper positions reviewed: PT-20260608-076, PT-20260608-077, PT-20260608-078, PT-20260608-079, PT-20260608-080, PT-20260608-081, PT-20260608-082, PT-20260608-083, PT-20260609-084, PT-20260609-085, PT-20260609-086, PT-20260609-087, and PT-20260609-088.
- Market prices came from browser-readable and search-rendered Polymarket pages. Executable order-book depth was not independently verified, and several localized pages disagreed materially.
- Weather evidence came from HKO current/max data and local forecast, NWS point forecasts for KHOU/KLGA/KATL/KORD/KMIA, and Met Office London City Airport guidance.

## Top edges

1. Hong Kong Observatory Jun 9 30C NO: strongest current paper-only add-on.
   - Current price: readable Polymarket pages ranged from about 30C Yes 24-33c / No 69-77c.
   - Implied probability: about 69-77% NO.
   - Estimated fair value: 90-97% NO.
   - Estimated edge: roughly +13 to +28 percentage points.
   - Confidence: Medium to medium-high.
   - Key reasoning: HKO current weather showed the Observatory at 27C at 14:00 HKT, and the since-midnight max/min file still showed HK Observatory max only 27.0C through 14:00 HKT. The 14:45 HKT local forecast remained mainly cloudy with a few showers, which makes a late push to 30.0C+ increasingly difficult.
   - Liquidity/practicality notes: opened PT-20260609-089 as a $10 simulated BUY_NO at 72c. Size stays tiny because pages conflict, HKO data is provisional, final Daily Extract treatment can differ, and the paper book already has HKO exposure.

2. Houston KHOU Jun 9 90-91F YES: represented moderate edge, no duplicate add.
   - Current price: readable pages ranged around 30-42c for 90-91F YES, with 88-89F also live around the low-30s to low-40s.
   - Implied probability: about 30-42% YES.
   - Estimated fair value: 43-53% YES.
   - Estimated edge: roughly +1 to +23 points, strongest only on the low pages.
   - Confidence: Medium-low.
   - Key reasoning: NWS Houston Hobby guidance is mostly sunny with a high near 91F and only a slight afternoon thunderstorm chance, but 88-89F remains a live cap path and 92F+ remains a warm miss path.
   - Liquidity/practicality notes: PT-20260609-087 already holds 90-91F from 40c. No duplicate.

3. NYC KLGA Jun 9 80-81F YES: represented moderate edge, no duplicate add.
   - Current price: readable pages ranged roughly 29-31c for 80-81F YES, with 78-79F and 82-83F pages conflicting.
   - Implied probability: about 29-31% YES.
   - Estimated fair value: 35-45% YES.
   - Estimated edge: roughly +4 to +16 points.
   - Confidence: Medium-low.
   - Key reasoning: NWS LaGuardia guidance is sunny with a high near 80F and south wind 9-15 mph, keeping the 78-81F cluster central and 80-81F the cleaner represented bucket.
   - Liquidity/practicality notes: PT-20260608-080 already holds 80-81F from 28c. No duplicate because NYC exposure is concentrated.

4. Atlanta KATL Jun 9 84-85F YES: revived represented edge, no duplicate add.
   - Current price: readable pages ranged around 18-23c for 84-85F YES, with 82-83F around 36-38c and 80-81F around 24-27c.
   - Implied probability: about 18-23% YES.
   - Estimated fair value: 23-33% YES.
   - Estimated edge: roughly 0 to +15 points.
   - Confidence: Low to medium-low.
   - Key reasoning: NWS Atlanta guidance shows a high near 84F, but showers/thunderstorms are likely and can easily cap the station in 80-83F. This revives, but does not cleanly strengthen, the older 84-85F thesis.
   - Liquidity/practicality notes: PT-20260608-081 already holds 84-85F from 16c. No duplicate because storms and page conflict keep the edge fragile.

5. London EGLC Jun 9 19C YES: represented weak-to-moderate edge, no duplicate add.
   - Current price: current pages show 19C around 19-22c, with 18C leading around 39-44c and 17C around 25-30c.
   - Implied probability: about 19-22% YES.
   - Estimated fair value: 20-30% YES.
   - Estimated edge: roughly 0 to +11 points.
   - Confidence: Low.
   - Key reasoning: Met Office London City Airport daily card still lists today's maximum at 19C, while the hourly table peaks at 18C. Exact-Celsius settlement remains fragile.
   - Liquidity/practicality notes: PT-20260608-079 and PT-20260608-082 already represent 19C from 21c and 10c. No more same-thesis London exposure.

6. Chicago KORD Jun 9 86-87F YES: represented but only thinly positive after repricing.
   - Current price: current pages ranged from about 22c to 37c; fresher higher-volume snippets put 86-87F around 36-37c.
   - Implied probability: roughly 22-37% YES.
   - Estimated fair value: 37-47% YES.
   - Estimated edge: positive only if the lower page is live; modest at the fresher 36-37c quote.
   - Confidence: Low to medium-low.
   - Key reasoning: NWS O'Hare guidance has a high near 86F after early clouds/showers, which supports 86-87F, but the market has mostly moved toward that center.
   - Liquidity/practicality notes: PT-20260608-078 already holds 86-87F from 22c. PT-20260609-084 on 88-89F remains a tracking hedge.

7. Miami KMIA Jun 9 88-89F cluster: no fresh edge.
   - Current price: fresher pages put 88-89F around 43-50c and 90-91F around 14-22c.
   - Implied probability: about 43-50% for 88-89F.
   - Estimated fair value: 43-55% for 88-89F.
   - Estimated edge: near fair after spread.
   - Confidence: Low to medium-low.
   - Key reasoning: NWS Miami guidance is high near 89F with a 20% afternoon shower/thunderstorm chance, so 88-89F is reasonable but no longer discounted. PT-20260608-077 on 90-91F remains tracking/adverse-to-neutral.

## Recommended paper trades

Opened one new paper-only simulated trade:

- PT-20260609-089: Hong Kong Observatory Jun 9 30C NO at 72c, $10 simulated notional. Thesis: official HKO current/max data still show only 27.0C at the Observatory by 14:00 HKT, and the updated 14:45 HKT local forecast remains mainly cloudy with a few showers, making 30.0C+ materially less likely than Polymarket's 30C Yes price around 24-33c implies. Confidence medium to medium-high. Invalidation risks: fast late-afternoon clearing/heating; final Daily Extract differs from provisional max/min data; Polymarket quote is stale or not executable; this adds to an already hedged HKO cluster.

Maintained without duplicate adds:

- PT-20260609-086 and PT-20260609-088, Hong Kong Observatory Jun 9 30C NO: both remain evidence-supported.
- PT-20260608-083, Hong Kong Observatory Jun 9 30C YES: adverse/tracking and offset by the NO paper hedges.
- PT-20260609-087, Houston KHOU Jun 9 90-91F YES: represented moderate edge but no duplicate.
- PT-20260608-080, NYC KLGA Jun 9 80-81F YES: maintained as the cleaner NYC bucket.
- PT-20260608-076 and PT-20260609-085, NYC KLGA Jun 9 82-83F YES: tracking/uncertain.
- PT-20260608-081, Atlanta KATL Jun 9 84-85F YES: revived but still fragile; no duplicate.
- PT-20260608-078 and PT-20260609-084, Chicago KORD Jun 9 86-87F YES / 88-89F YES: 86-87F is cleaner; 88-89F remains tracking.
- PT-20260608-079 and PT-20260608-082, London EGLC Jun 9 19C YES: represented but fragile.
- PT-20260608-077, Miami KMIA Jun 9 90-91F YES: tracking/adverse-to-neutral.

No real trades or betting actions were executed.

## Risks and invalidation factors

- Exact weather buckets can flip on one station degree or one Celsius decimal boundary.
- Browser-readable Polymarket pages can be stale and may not match executable order-book depth.
- HKO since-midnight data is provisional; final Daily Extract can differ.
- Wunderground final histories can differ from NWS/Met Office/HKO intraday or forecast data.
- Polymarket pages remain materially conflicted for Hong Kong, Houston, NYC, Atlanta, Chicago, London, and Miami.
- The paper book remains concentrated in June 9 weather buckets, so fresh simulated sizing remains tiny.

## Sources used

- Polymarket Hong Kong Jun 9: https://polymarket.com/zh-hant/event/highest-temperature-in-hong-kong-on-june-9-2026?marketSlug=highest-temperature-in-hong-kong-on-june-9-2026-30c&outcomeIndex=1
- HKO current weather API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=rhrread&lang=en
- HKO since-midnight max/min data: https://data.weather.gov.hk/weatherAPI/hko_data/regional-weather/latest_since_midnight_maxmin.csv
- HKO local forecast API: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=flw&lang=en
- NWS Houston Hobby Airport: https://forecast.weather.gov/MapClick.php?lat=29.65000&lon=-95.28000
- NWS New York LaGuardia Airport: https://forecast.weather.gov/MapClick.php?lat=40.77917&lon=-73.88
- NWS Atlanta: https://forecast.weather.gov/MapClick.php?CityName=Atlanta&state=GA&textField1=33.74463&textField2=-84.37577
- NWS Chicago O'Hare Airport: https://forecast.weather.gov/MapClick.php?lat=41.97972&lon=-87.90444
- NWS Miami International Airport: https://forecast.weather.gov/MapClick.php?lat=25.782512&lon=-80.296165
- Met Office London City Airport: https://weather.metoffice.gov.uk/forecast/u10j124jp
- Polymarket Houston Jun 9: https://polymarket.com/zh/event/highest-temperature-in-houston-on-june-9-2026/highest-temperature-in-houston-on-june-9-2026-90-91f
- Polymarket NYC Jun 9: https://polymarket.com/vi/event/highest-temperature-in-nyc-on-june-9-2026
- Polymarket Atlanta Jun 9: https://polymarket.com/vi/event/highest-temperature-in-atlanta-on-june-9-2026?marketSlug=highest-temperature-in-atlanta-on-june-9-2026-82-83f&outcomeIndex=1
- Polymarket Chicago Jun 9: https://polymarket.com/vi/event/highest-temperature-in-chicago-on-june-9-2026/highest-temperature-in-chicago-on-june-9-2026-84-85f
- Polymarket London Jun 9: https://polymarket.com/vi/event/highest-temperature-in-london-on-june-9-2026?marketSlug=highest-temperature-in-london-on-june-9-2026-18c&outcomeIndex=1
- Polymarket Miami Jun 9: https://polymarket.com/vi/event/highest-temperature-in-miami-on-june-9-2026?marketSlug=highest-temperature-in-miami-on-june-9-2026-88-89f&outcomeIndex=0

## Repo log update

GitHub log files:

- Updated odds/latest.md.
- Added odds/history/2026-06-09T0708Z.md.
- Added alerts/2026-06-09T0708Z.md.
- Added data/market_snapshots/2026-06-09T0708Z.json.
- Added paper_trading/entries/2026-06-09T0708Z.md.
- Added paper_trading/maintenance/2026-06-09T0708Z.md.
- Added paper_trading/ledger_appends/2026-06-09T0708Z.csv.
- Updated paper_trading/paper_trade_summary.md.

Local memory also updated the full paper_trade_log, watchlist, edge notes, paper summaries, and working notes.

Opened paper-only PT-20260609-089. No real trades or betting actions executed.
