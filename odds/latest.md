# Odds Market Snapshot

## Time checked

2026-06-08 11:08 UTC / 2026-06-08 19:08 HKT.

Scheduled run invoked at 2026-06-08 19:07 HKT. Evidence checked through 11:08 UTC. No real trades, bets, wallet actions, order submissions, or execution integrations were used.

## Markets monitored

- Polymarket station-resolved highest-temperature markets for June 8, 2026: Hong Kong Observatory, Miami KMIA, NYC KLGA, Chicago KORD, London EGLC, Houston KHOU, and Atlanta KATL.
- Existing June 8 paper positions reviewed: Hong Kong 29C YES and 30C YES; Chicago 82-83F YES and 84-85F YES; NYC 78-79F YES; Miami 90-91F YES; Atlanta 78-79F YES and 80-81F YES; Houston 88-89F YES; London 17C YES and 19C YES.
- Market prices came from browser/search-rendered Polymarket pages. Direct Polymarket API/page fetches from the workspace were blocked by a 403 tunnel response, so executable order-book depth was not independently verified.
- Weather evidence came from HKO regional readings and forecast, NWS point forecasts/current conditions, and Met Office London City Airport.

## Top edges

1. Hong Kong Observatory Jun 8 30C YES: strongest edge, small paper add opened.
   - Current price: current visible Polymarket page shows 30C at 31% / buy Yes 32c, with 29C at 25%, 31C at 23%, and 32C at 10.3%; other localized pages remain stale/conflicted around roughly 21-32c for 30C.
   - Implied probability: about 31-32% on the cleanest current page.
   - Estimated fair value: 82-90% YES, assuming the 30C bucket covers a 30.0-30.9C official high.
   - Estimated edge: roughly +50 to +59 percentage points.
   - Confidence: Medium.
   - Key reasoning: HKO regional readings at 18:50 HKT show HK Observatory at 28.3C with max/min since midnight of 30.9C / 26.4C. HKO current readings at 18:00 HKT showed the Observatory down to 28C with Thunderstorm Warning active, and the local forecast says heavy showers and squally thunderstorms will persist tonight/tomorrow morning. With sunset and near-zero solar context, a late move to 31.0C+ is now much less likely than a 30.xC final high.
   - Liquidity/practicality notes: PT-20260607-069 and PT-20260608-073 already represented this thesis from 26c and 23c. A third, still-small paper add was justified because the station-specific max-since-midnight table materially strengthened the evidence. No real trade was executed.

2. Miami KMIA Jun 8 90-91F YES: represented quote-sensitive edge, no fourth add.
   - Current price: visible pages conflict, with 90-91F shown around 16-25% and buy Yes roughly 17-31c; 88-89F often leads.
   - Implied probability: roughly 16-31%, depending on which page is live.
   - Estimated fair value: 30-42% YES.
   - Estimated edge: roughly -1 to +25 percentage points; only attractive if the lower 17c quote is live.
   - Confidence: Low to medium-low.
   - Key reasoning: NWS KMIA shows current conditions at 80F at 05:53 EDT and Today high near 90F with mostly sunny conditions and east wind. That keeps 90-91F alive, but east wind/sea-breeze risk makes 88-89F a serious miss path.
   - Liquidity/practicality notes: PT-20260607-058, PT-20260607-062, and PT-20260607-066 already cover the thesis. No fourth same-thesis paper add while pages conflict.

3. NYC KLGA Jun 8 76-77F YES: best fresh hedge signal, watch-only.
   - Current price: visible pages show 76-77F around 32-43%, with 78-79F ranging from the low 20s to high 30s across localized pages.
   - Implied probability: roughly 32-43%.
   - Estimated fair value: 40-52% YES.
   - Estimated edge: roughly -3 to +20 percentage points.
   - Confidence: Low to medium-low.
   - Key reasoning: NWS KLGA shows 64F at 06:51 EDT, NE wind 12 mph, and Today high near 77F with northeast wind becoming east. This now supports 76-77F more than the older 78-79F paper thesis, but 74-75F and 78-79F remain realistic adjacent outcomes.
   - Liquidity/practicality notes: no new NYC exposure because the paper book is already concentrated in KLGA Jun 8 78-79F positions.

4. Chicago KORD Jun 8 82-83F YES: represented moderate edge, no duplicate.
   - Current price: current visible Polymarket page shows 82-83F around 34% / buy Yes 35c; other localized pages have shown 37-40c.
   - Implied probability: roughly 34-40%.
   - Estimated fair value: 40-50% YES.
   - Estimated edge: roughly 0 to +16 percentage points.
   - Confidence: Medium-low.
   - Key reasoning: NWS KORD shows light rain at 66F at 02:51 CDT and Monday high near 83F with showers/thunderstorms likely, then storms after 4pm. This keeps 82-83F plausible but leaves 80-81F rain-cap risk and 84-85F pre-rain-warming risk live.
   - Liquidity/practicality notes: PT-20260608-071 already holds 82-83F from 35c. No duplicate near the same quote.

5. London EGLC Jun 8 17C YES: represented small edge, no duplicate.
   - Current price: visible Polymarket pages show 17C around 41% and 18C around 28-37%.
   - Implied probability: about 41% for 17C on the cleaner current page.
   - Estimated fair value: 43-53% YES.
   - Estimated edge: roughly +2 to +12 percentage points.
   - Confidence: Low to medium-low.
   - Key reasoning: Met Office London City Airport shows Today max 18C, but the hourly table from 11am through 11pm peaks at 17C around 6pm with heavy rain earlier. That keeps 17C/18C as the real contest and leaves the older 19C thesis adverse.
   - Liquidity/practicality notes: PT-20260608-070 already holds 17C from 37c. No add at 41c.

6. Houston KHOU Jun 8 88-89F YES: represented small edge, near fair.
   - Current price: current visible Polymarket page shows 88-89F around 40% / buy Yes 41c, with 86-87F around 37% / buy Yes 41c.
   - Implied probability: about 40-41%.
   - Estimated fair value: 44-54% YES.
   - Estimated edge: roughly +3 to +14 percentage points.
   - Confidence: Low to medium-low.
   - Key reasoning: NWS KHOU shows 81F at 01:53 CDT, overcast, and Today high near 88F. That supports 88-89F, but persistent cloud and high humidity keep 86-87F live.
   - Liquidity/practicality notes: PT-20260607-059 already represents the thesis from 32c. No add near 41c.

## No-edge or downgraded markets

- Hong Kong Observatory Jun 8 29C YES: adverse/tracking. HKO now shows max since midnight 30.9C at HK Observatory, making 29C unlikely unless final resolution treatment differs materially.
- Hong Kong Observatory Jun 8 31C YES: live but likely overvalued around 23c if 30.9C remains the final high. No separate NO entry was opened because it overlaps the 30C YES paper thesis and executable quotes were not verified.
- Atlanta KATL Jun 8 80-81F YES: close to fair. Current visible page shows 80-81F around 40c and NWS high near 81F with 80% shower/thunderstorm risk.
- NYC KLGA Jun 8 78-79F YES: downgraded/tracking after NWS guidance centered closer to 77F.
- London EGLC Jun 8 19C YES: tracking/adverse after current Met Office guidance cooled into the 17-18C cluster.
- Chicago KORD Jun 8 84-85F YES: hedged/tracking because official guidance remains centered closer to 83F.

## Recommended paper trades

Opened one new paper-only position:

- PT-20260608-075: Hong Kong Observatory Jun 8 30C YES.
  - Simulated stance: BUY_YES.
  - Simulated size: $20 notional.
  - Entry price: 32c.
  - Thesis: HKO's 18:50 HKT regional table shows HK Observatory max since midnight at 30.9C, current temperature at 28.3C, and storm/rain context that makes a late 31.0C+ print unlikely. Visible Polymarket pricing still implied only about 31-32%.
  - Confidence: Medium.
  - Invalidation risks: final HKO/Wunderground/Polymarket resolution could round 30.9C into 31C; an unobserved or later 31.0C+ print could appear; HKO regional data is provisional; browser-visible Polymarket prices may be stale or not executable; this adds to an already represented HKO 30C thesis.

Maintained or downgraded existing paper positions:

- PT-20260607-069, PT-20260608-073, and PT-20260608-075: Hong Kong 30C YES maintained as the top cluster.
- PT-20260607-057: Hong Kong 29C YES adverse/tracking.
- PT-20260608-071: Chicago 82-83F YES maintained only.
- PT-20260607-056: Chicago 84-85F YES hedged/tracking.
- PT-20260607-061, PT-20260607-064, PT-20260607-068, and PT-20260608-072: NYC 78-79F YES tracking/uncertain; no additional NYC exposure.
- PT-20260607-058, PT-20260607-062, and PT-20260607-066: Miami 90-91F YES maintained; no fourth add.
- PT-20260607-065: Atlanta 80-81F YES maintained, now close to fair.
- PT-20260607-063: Atlanta 78-79F YES tracking/hedged.
- PT-20260607-059: Houston 88-89F YES maintained, now mild edge/near fair.
- PT-20260608-070: London 17C YES maintained.
- PT-20260607-060 and PT-20260607-067: London 19C YES tracking/adverse.

No real trades or betting actions were executed.

## Risks and invalidation factors

- Exact weather buckets can flip on one station degree, one Celsius decimal, or resolution-source rounding.
- HKO regional readings are provisional and may differ from final daily extract or Polymarket's chosen resolution handling.
- Wunderground final daily histories may differ from NWS, Met Office, HKO intraday readings, or browser-visible pages.
- Browser/search-rendered Polymarket prices may be stale and may not match executable order-book depth.
- The new HKO add is correlated with existing HKO 30C paper entries, so sizing remains small despite the large apparent edge.

## Sources used

- Polymarket Hong Kong Jun 8: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-8-2026
- HKO regional weather readings: https://www.weather.gov.hk/textonly/v2/forecast/text_readings_e.htm
- HKO current readings: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=rhrread&lang=en
- HKO local forecast: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=flw&lang=en
- Polymarket Miami Jun 8: https://polymarket.com/event/highest-temperature-in-miami-on-june-8-2026
- NWS KMIA forecast: https://forecast.weather.gov/zipcity.php?inputstring=KMIA
- Polymarket NYC Jun 8: https://polymarket.com/event/highest-temperature-in-nyc-on-june-8-2026
- NWS KLGA forecast: https://forecast.weather.gov/zipcity.php?inputstring=KLGA
- Polymarket Chicago Jun 8: https://polymarket.com/event/highest-temperature-in-chicago-on-june-8-2026
- NWS KORD forecast: https://forecast.weather.gov/zipcity.php?inputstring=KORD
- Polymarket London Jun 8: https://polymarket.com/event/highest-temperature-in-london-on-june-8-2026
- Met Office London City Airport: https://weather.metoffice.gov.uk/forecast/u10j124jp
- Polymarket Houston Jun 8: https://polymarket.com/event/highest-temperature-in-houston-on-june-8-2026
- NWS KHOU forecast: https://forecast.weather.gov/zipcity.php?inputstring=KHOU
- Polymarket Atlanta Jun 8: https://polymarket.com/event/highest-temperature-in-atlanta-on-june-8-2026
- NWS KATL forecast: https://forecast.weather.gov/zipcity.php?inputstring=KATL

## Repo log update

GitHub/memory log files:

- Updated odds/latest.md.
- Added odds/history/2026-06-08T1108Z.md.
- Added alerts/2026-06-08T1108Z.md.
- Added data/market_snapshots/2026-06-08T1108Z.json.
- Added paper_trading/maintenance/2026-06-08T1108Z.md.
- Added paper_trading/ledger_appends/2026-06-08T1108Z.csv with PT-20260608-075.

Memory notes additionally updated:

- paper_trading/paper_trade_summary.md.
- paper_trading/paper_trade_log.md.
- paper-trade-summary.md.
- market-watchlist.md.
- edge-notes.md.

No real trades or betting actions executed.
