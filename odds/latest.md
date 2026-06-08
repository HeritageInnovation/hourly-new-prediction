# Odds Market Snapshot

## Time checked

2026-06-08 19:08 UTC / 2026-06-09 03:08 HKT.

Scheduled run invoked at 2026-06-09 03:07 HKT. Evidence checked through 19:08 UTC. No real trades, bets, wallet actions, order submissions, or execution integrations were used.

## Markets monitored

- Polymarket station-resolved highest-temperature markets for June 9, 2026: NYC KLGA, Atlanta KATL, Chicago KORD, Miami KMIA, London EGLC, Houston KHOU, and Hong Kong Observatory.
- Existing June 9 paper positions reviewed: PT-20260608-076, PT-20260608-077, PT-20260608-078, and PT-20260608-079.
- Market prices came from browser/search-rendered Polymarket pages. Direct executable order-book depth was not independently verified.
- Weather evidence came from NWS point forecasts, Met Office London City Airport guidance, and HKO forecasts/current readings.

## Top edges

1. NYC KLGA Jun 9 80-81F YES: moderate edge, small paper hedge opened.
   - Current price: Polymarket localized pages showed 80-81F around 28-31%, with cleaner buy Yes quotes around 28-31c.
   - Implied probability: about 28-31%.
   - Estimated fair value: 40-50% YES.
   - Estimated edge: roughly +9 to +22 percentage points.
   - Confidence: Medium-low.
   - Key reasoning: NWS KLGA forecasts Tuesday sunny with high near 80F and south wind around 6 mph. That weakens the prior 82-83F paper thesis and makes the adjacent 80-81F bucket the cleaner hedge.
   - Liquidity/practicality notes: opened PT-20260608-080 as a $10 paper-only BUY_YES at 28c. Exact station bucket risk remains high, and prior NYC exposure keeps size small.

2. Atlanta KATL Jun 9 84-85F YES: quote-sensitive moderate edge, tiny paper add opened.
   - Current price: the cleanest readable Polymarket page showed 84-85F around 15% with buy Yes around 16c; another localized page showed a higher/conflicting 23c area.
   - Implied probability: about 16% on the cleanest buy quote.
   - Estimated fair value: 26-38% YES.
   - Estimated edge: roughly +10 to +22 percentage points if the low quote is live; thinner if only the higher page is executable.
   - Confidence: Low.
   - Key reasoning: NWS KATL now forecasts Tuesday high near 84F with showers/thunderstorms likely mainly 2pm-5pm. That puts 84-85F live if enough pre-storm heating occurs, while storms still leave 82-83F as a serious miss.
   - Liquidity/practicality notes: opened PT-20260608-081 as a $10 paper-only BUY_YES at 16c. Size is tiny because quote quality and outcome volume are weak.

3. Chicago KORD Jun 9 86-87F YES: represented moderate edge, no duplicate add.
   - Current price: Polymarket pages showed 86-87F roughly 19-22% displayed, with buy Yes quotes ranging about 22-38c depending on localized page.
   - Implied probability: about 22-38%.
   - Estimated fair value: 32-44% YES.
   - Estimated edge: attractive on the low pages, close to fair on the higher buy quotes.
   - Confidence: Low to medium-low.
   - Key reasoning: NWS O'Hare forecast still centers Tuesday near 86F, with showers mainly before 7am and partly sunny conditions afterward.
   - Liquidity/practicality notes: PT-20260608-078 already represents the thesis from 22c. No duplicate because the current clean quote is not clearly better than entry and pages disagree.

4. Miami KMIA Jun 9 90-91F YES: represented quote-sensitive edge, no duplicate add.
   - Current price: Polymarket pages showed 90-91F around 13-22%, with buy Yes roughly 14-32c across localized pages.
   - Implied probability: about 14-32%.
   - Estimated fair value: 24-36% YES.
   - Estimated edge: meaningful only if the low 14-18c pages are live.
   - Confidence: Low to medium-low.
   - Key reasoning: NWS KMIA keeps Tuesday high near 90F with partly sunny conditions, east wind, and only a 20% late-day thunderstorm chance. Sea-breeze cap risk keeps 88-89F live.
   - Liquidity/practicality notes: PT-20260608-077 already represents the thesis from 14c. No duplicate.

5. London EGLC Jun 9 19C YES: represented moderate/weak edge, no duplicate add.
   - Current price: current Polymarket pages mostly showed 19C around 21-22%, with 18C leading around 40%.
   - Implied probability: about 21-22%.
   - Estimated fair value: 26-36% YES.
   - Estimated edge: roughly +4 to +15 percentage points.
   - Confidence: Low to medium-low.
   - Key reasoning: Met Office London City Airport daily view still supports a 19C maximum, but the hourly table peaks at 18C. That keeps the 19C edge live but capped.
   - Liquidity/practicality notes: PT-20260608-079 already holds 19C YES from 21c. No duplicate.

6. Houston KHOU Jun 9 90-91F YES: mild watch-only edge.
   - Current price: Polymarket pages showed 90-91F roughly 30-35%, with buy Yes around 33-38c; some pages also showed higher/conflicted prices.
   - Implied probability: about 33-38%.
   - Estimated fair value: 34-46% YES.
   - Estimated edge: flat to about +13 percentage points.
   - Confidence: Low to medium-low.
   - Key reasoning: NWS KHOU forecasts Tuesday mostly sunny with high near 90F and heat index values as high as 101F, but 88-89F remains a live adjacent miss.
   - Liquidity/practicality notes: no paper entry; current price is too close after spread and exact-bucket risk.

7. Hong Kong Observatory Jun 9 29C YES: near-fair watch-only.
   - Current price: Polymarket pages showed 29C around 39-40%, with 28C and 30C both live.
   - Implied probability: about 39-40%.
   - Estimated fair value: 38-50% YES.
   - Estimated edge: roughly flat to +11 percentage points.
   - Confidence: Low to medium-low.
   - Key reasoning: HKO forecasts Tuesday 25-29C with heavy showers and squally thunderstorms at first, easing later. The 29C bucket is plausible but not cheap enough versus 28C/30C boundary risk.
   - Liquidity/practicality notes: no paper entry.

## Recommended paper trades

Opened two new paper-only simulated positions:

- PT-20260608-080: NYC KLGA Jun 9 80-81F YES.
  - Simulated stance: BUY_YES.
  - Simulated size: $10 notional.
  - Entry price: 28c.
  - Thesis: NWS KLGA shifted/held Tuesday around a sunny high near 80F while Polymarket still priced 80-81F in the high-20s. This also hedges the older 82-83F YES paper position after the forecast cooled.
  - Confidence: Medium-low.
  - Invalidation risks: KLGA caps at 78-79F under cooler local flow; warmer inland mixing pushes 82F+; browser-visible quote is stale or not executable; Wunderground final history differs from NWS point forecast.

- PT-20260608-081: Atlanta KATL Jun 9 84-85F YES.
  - Simulated stance: BUY_YES.
  - Simulated size: $10 notional.
  - Entry price: 16c.
  - Thesis: NWS KATL now centers Tuesday near 84F, while the cleanest readable Polymarket page left 84-85F near 16c. The market may be slow to update from the prior cooler 82-83F cluster.
  - Confidence: Low.
  - Invalidation risks: thunderstorms/clouds arrive early and cap the station at 82-83F; storm timing shifts later and pushes 86F+; the low Polymarket quote is stale, malformed, or not executable; low volume makes the displayed edge fragile.

Maintained without duplicate adds:

- PT-20260608-078, Chicago KORD Jun 9 86-87F YES at 22c.
- PT-20260608-077, Miami KMIA Jun 9 90-91F YES at 14c.
- PT-20260608-079, London EGLC Jun 9 19C YES at 21c.
- PT-20260608-076, NYC KLGA Jun 9 82-83F YES at 14c: remains tracking/adverse-to-neutral after the NWS forecast centered nearer 80F.

No real trades or betting actions were executed.

## Risks and invalidation factors

- Exact weather buckets can flip on one station degree or one Celsius decimal boundary.
- Wunderground final daily histories can differ from NWS, Met Office, HKO intraday readings, or browser-visible pages.
- Browser/search-rendered Polymarket prices may be stale and may not match executable order-book depth.
- Several localized Polymarket pages disagree materially, especially Atlanta, Miami, Chicago, NYC, and London.
- New simulated size is intentionally small because the book is already clustered in station-temperature markets.

## Sources used

- Polymarket NYC Jun 9: https://polymarket.com/tl/event/highest-temperature-in-nyc-on-june-9-2026/highest-temperature-in-nyc-on-june-9-2026-80-81f
- NWS KLGA forecast: https://forecast.weather.gov/zipcity.php?inputstring=KLGA
- Polymarket Atlanta Jun 9: https://polymarket.com/tl/event/highest-temperature-in-atlanta-on-june-9-2026/highest-temperature-in-atlanta-on-june-9-2026-84-85f
- NWS KATL forecast: https://forecast.weather.gov/zipcity.php?inputstring=KATL
- Polymarket Chicago Jun 9: https://polymarket.com/tl/event/highest-temperature-in-chicago-on-june-9-2026/highest-temperature-in-chicago-on-june-9-2026-86-87f
- NWS KORD forecast: https://forecast.weather.gov/zipcity.php?inputstring=KORD
- Polymarket Miami Jun 9: https://polymarket.com/tl/event/highest-temperature-in-miami-on-june-9-2026/highest-temperature-in-miami-on-june-9-2026-90-91f
- NWS KMIA forecast: https://forecast.weather.gov/zipcity.php?inputstring=KMIA
- Polymarket London Jun 9: https://polymarket.com/tl/event/highest-temperature-in-london-on-june-9-2026
- Met Office London City Airport: https://weather.metoffice.gov.uk/forecast/u10j124jp
- Polymarket Houston Jun 9: https://polymarket.com/tl/event/highest-temperature-in-houston-on-june-9-2026
- NWS KHOU forecast: https://forecast.weather.gov/zipcity.php?inputstring=KHOU
- Polymarket Hong Kong Jun 9: https://polymarket.com/tl/event/highest-temperature-in-hong-kong-on-june-9-2026
- HKO local forecast: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=flw&lang=en
- HKO 9-day forecast: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=fnd&lang=en
- HKO current readings: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=rhrread&lang=en

## Repo log update

GitHub/memory log files:

- Updated odds/latest.md.
- Added odds/history/2026-06-08T1908Z.md.
- Added alerts/2026-06-08T1908Z.md.
- Added data/market_snapshots/2026-06-08T1908Z.json.
- Added paper_trading/entries/2026-06-08T1908Z.md.
- Added paper_trading/maintenance/2026-06-08T1908Z.md.
- Added paper_trading/ledger_appends/2026-06-08T1908Z.csv with PT-20260608-080 and PT-20260608-081.

Memory notes additionally updated:

- paper_trading/paper_trade_summary.md.
- paper_trading/paper_trade_log.md.
- paper-trade-summary.md.
- market-watchlist.md.
- edge-notes.md.

No real trades or betting actions executed.