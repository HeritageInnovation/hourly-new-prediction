# Odds Market Snapshot

## Time checked

2026-06-07 23:12 UTC / 2026-06-08 07:12 HKT

Scheduled run invoked at 2026-06-08 07:07 HKT. Evidence checked through 23:12 UTC. No real trades, bets, wallet actions, order submissions, or execution integrations were used.

## Markets monitored

- Polymarket station-resolved highest-temperature markets for June 8, 2026: NYC KLGA, Hong Kong Observatory, London EGLC, Houston KHOU, Atlanta KATL, Miami KMIA, and Chicago KORD.
- Existing June 8 paper positions reviewed: NYC 78-79F YES, Hong Kong 29C YES, London 19C YES, Houston 88-89F YES, Atlanta 78-79F YES and 80-81F YES, Miami 90-91F YES, and Chicago 84-85F YES.
- Market prices came from browser-readable Polymarket pages/search snapshots. Official evidence came from NWS point forecasts/current conditions, Met Office London City Airport, and HKO open-data forecasts/current readings.
- Live executable order-book depth was not independently available; browser-readable Polymarket prices may differ from executable quotes.

## Top edges

1. NYC KLGA Jun 8 78-79F YES: fresh tiny add-on.
   - Current price: Polymarket shows 78-79F at 18%, with buy Yes around 18c. 76-77F leads near 41% and 74-75F is near 32%.
   - Implied probability: about 18%.
   - Estimated fair value: 35-45% YES.
   - Estimated edge: roughly +17 to +27 percentage points.
   - Confidence: Medium-low.
   - Key reasoning: NWS KLGA Monday forecast remains sunny with high near 78F and northeast wind 9-13 mph. The market has moved probability toward 76-77F and 74-75F, but the official forecast center still lands inside 78-79F.
   - Liquidity/practicality notes: event volume is roughly $15.2K and the 78-79F outcome shows about $2.1K volume, but this is a third same-thesis paper add-on. Opened PT-20260607-068 at 18c for $15 simulated notional only.

2. Hong Kong Observatory Jun 8 30C YES: fresh adjacent-bucket hedge.
   - Current price: Polymarket shows 30C at 25%, with buy Yes around 26c; 29C is near 27%, 31C near 21%, and 32C near 14%.
   - Implied probability: about 26%.
   - Estimated fair value: 32-42% YES.
   - Estimated edge: roughly +6 to +16 percentage points.
   - Confidence: Low to medium-low.
   - Key reasoning: HKO's 05:50 HKT forecast lists Monday maximum temperature at 30C with mainly cloudy weather, occasional heavy showers, and squally thunderstorms. The 06:00 HKT current reading at the Observatory was 27C with thunderstorm warning still active. That supports shifting the prior 29C-only thesis into a 29C/30C cluster, with 30C now the cleaner hedge.
   - Liquidity/practicality notes: event volume is roughly $54.2K and 30C outcome volume is about $5.9K. Opened PT-20260607-069 at 26c for $15 simulated notional because one-decimal boundary risk remains meaningful.

3. London EGLC Jun 8 19C YES: represented edge, no duplicate.
   - Current price: Polymarket shows 19C around 16%, with buy Yes around 16c. 18C leads near 44-45%, 17C is near 29-30%, and 16C is near 11%.
   - Implied probability: about 16%.
   - Estimated fair value: 24-34% YES.
   - Estimated edge: roughly +8 to +18 percentage points.
   - Confidence: Low to medium-low.
   - Key reasoning: Met Office London City Airport daily forecast still lists Monday max 19C, but the hourly table peaks at 18C. This keeps 19C underpriced but source-conflicted.
   - Liquidity/practicality notes: PT-20260607-060 and PT-20260607-067 already represent this thesis. No duplicate because the current 16c quote is above the sub-12c add trigger and hourly evidence has not strengthened.

4. Houston KHOU Jun 8 88-89F YES: represented, mostly converged.
   - Current price: Polymarket shows 88-89F around 39%, with buy Yes around 39c; 86-87F is near 36%.
   - Implied probability: about 39%.
   - Estimated fair value: 42-52% YES.
   - Estimated edge: roughly +3 to +13 percentage points.
   - Confidence: Medium-low.
   - Key reasoning: NWS KHOU Monday forecast remains partly sunny with high near 89F and south wind 10-15 mph. 88-89F is still the centered bucket, but the price has moved closer to fair and 86-87F remains a live cooler miss.
   - Liquidity/practicality notes: PT-20260607-059 already holds 88-89F YES from 32c. No duplicate above entry.

## No-edge or downgraded markets

- Atlanta KATL Jun 8 80-81F YES is now near fair after repricing: Polymarket displays 80-81F at 39% with buy Yes around 42c, while NWS KATL shows high near 80F with showers and thunderstorms likely mainly after 2pm. Maintain PT-20260607-065 from 12c only.
- Miami KMIA Jun 8 90-91F YES is close to fair after repricing: Polymarket displays 90-91F near 39% with buy Yes around 40c, while NWS KMIA shows high near 90F with east wind. Maintain PT-20260607-058/PT-20260607-062/PT-20260607-066 only.
- Chicago KORD Jun 8 82-83F is close to fair: Polymarket displays 82-83F near 34% with buy Yes around 36c, while NWS O'Hare-area guidance shows high near 83F with showers/thunderstorms likely. Existing PT-20260607-056 on 84-85F remains tracking/less favorable.
- Atlanta KATL Jun 8 78-79F YES remains tracking/hedged because NWS guidance now centers closer to 80F.
- Hong Kong Observatory Jun 8 29C YES remains open from 23c but is no longer the cleanest single bucket after HKO shifted the max forecast to 30C.

## Recommended paper trades

Opened two new paper-only positions:

- PT-20260607-068: NYC KLGA Jun 8 78-79F YES at 18c, $15 simulated notional.
- PT-20260607-069: Hong Kong Observatory Jun 8 30C YES at 26c, $15 simulated notional.

No real trades or betting actions were executed.

## Sources used

- Polymarket NYC Jun 8: https://polymarket.com/tl/event/highest-temperature-in-nyc-on-june-8-2026
- NWS KLGA point forecast: https://forecast.weather.gov/MapClick.php?lat=40.77917&lon=-73.88
- Polymarket Hong Kong Jun 8: https://polymarket.com/es/event/highest-temperature-in-hong-kong-on-june-8-2026
- HKO 9-day forecast: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=fnd&lang=en
- HKO current readings: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=rhrread&lang=en
- Polymarket London Jun 8: https://polymarket.com/tl/event/highest-temperature-in-london-on-june-8-2026
- Met Office London City Airport: https://weather.metoffice.gov.uk/forecast/u10j124jp?new-design=false
- Polymarket Houston Jun 8: https://polymarket.com/tl/event/highest-temperature-in-houston-on-june-8-2026
- NWS KHOU point forecast: https://forecast.weather.gov/MapClick.php?lat=29.6454&lon=-95.2789
- Polymarket Atlanta Jun 8: https://polymarket.com/tl/event/highest-temperature-in-atlanta-on-june-8-2026
- NWS KATL point forecast: https://forecast.weather.gov/MapClick.php?lat=33.6367&lon=-84.4281
- Polymarket Miami Jun 8: https://polymarket.com/tl/event/highest-temperature-in-miami-on-june-8-2026
- NWS KMIA point forecast: https://forecast.weather.gov/MapClick.php?lat=25.78810&lon=-80.31690
- Polymarket Chicago Jun 8: https://polymarket.com/tl/event/highest-temperature-in-chicago-on-june-8-2026
- NWS Chicago/O'Hare-area point forecast: https://forecast.weather.gov/MapClick.php?lat=41.9142&lon=-87.9054

## Repo log update

Created/updated odds/latest.md, odds/history/2026-06-07T2312Z.md, alerts/2026-06-07T2312Z.md, data/market_snapshots/2026-06-07T2312Z.json, paper_trading/entries/2026-06-07T2312Z.md, paper_trading/maintenance/2026-06-07T2312Z.md, paper_trading/ledger_appends/2026-06-07T2312Z.csv, and paper_trading/paper_trade_summary.md. Opened paper-only PT-20260607-068 and PT-20260607-069. No real trades or betting actions executed.
