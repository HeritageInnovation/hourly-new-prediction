# Odds Market Snapshot

## Time checked

2026-06-08 00:12 UTC / 2026-06-08 08:12 HKT

Scheduled run invoked at 2026-06-08 08:07 HKT. Evidence checked through 00:12 UTC. No real trades, bets, wallet actions, order submissions, or execution integrations were used.

## Markets monitored

- Polymarket station-resolved highest-temperature markets for June 8, 2026: NYC KLGA, Hong Kong Observatory, London EGLC, Houston KHOU, Atlanta KATL, Miami KMIA, and Chicago KORD.
- Existing June 8 paper positions reviewed: NYC 78-79F YES, Hong Kong 29C YES and 30C YES, London 19C YES, Houston 88-89F YES, Atlanta 78-79F YES and 80-81F YES, Miami 90-91F YES, and Chicago 84-85F YES.
- Market prices came from browser-readable Polymarket pages/search snapshots. Several localized Polymarket pages disagreed, so quote ranges are used where appropriate.
- Official evidence came from NWS point forecasts/current conditions, Met Office London City Airport, and HKO open-data forecasts/current readings.
- Live executable order-book depth was not independently available; browser-readable Polymarket prices may differ from executable quotes.

## Top edges

1. Houston KHOU Jun 8 88-89F YES: maintained edge, no duplicate.
   - Current price: Polymarket readable pages/cards show 88-89F around 32-39%, with 86-87F close behind around 33-36%.
   - Implied probability: about 32-39%.
   - Estimated fair value: 42-52% YES.
   - Estimated edge: roughly +3 to +20 percentage points, depending on which quote is live.
   - Confidence: Medium-low.
   - Key reasoning: NWS KHOU forecast keeps Monday centered near 89F with partly sunny conditions and south wind 10-15 mph. That still favors 88-89F over 86-87F, but the quote picture is not clean enough for another paper add.
   - Liquidity/practicality notes: PT-20260607-059 already holds 88-89F YES from 32c. No duplicate unless a verified quote falls materially below entry or KHOU-specific evidence strengthens.

2. Miami KMIA Jun 8 90-91F YES: represented raw gap, quote-conflicted.
   - Current price: Polymarket readable pages show 90-91F around 20-31%, while 88-89F often leads.
   - Implied probability: about 20-31%.
   - Estimated fair value: 34-44% YES.
   - Estimated edge: roughly +3 to +24 percentage points, but highly quote-dependent.
   - Confidence: Low to medium-low.
   - Key reasoning: NWS KMIA forecast shows Monday high near 90F with mostly sunny conditions and east wind. That keeps 90-91F live, but east wind/sea-breeze risk leaves 88-89F as a plausible miss.
   - Liquidity/practicality notes: PT-20260607-058, PT-20260607-062, and PT-20260607-066 already represent this thesis. No fourth paper add unless a clean verified quote falls materially below 15c or KMIA evidence strengthens.

3. Hong Kong Observatory Jun 8 30C YES: maintained adjacent-bucket hedge.
   - Current price: Polymarket localized pages conflict, showing 30C roughly 25-34% and 29C roughly 24-27%.
   - Implied probability: about 25-34%.
   - Estimated fair value: 34-44% YES.
   - Estimated edge: roughly 0 to +19 percentage points, depending on which price is live.
   - Confidence: Low to medium-low.
   - Key reasoning: HKO 05:50 HKT nine-day forecast lists Monday max temperature at 30C, and the 07:45 HKT local forecast says the maximum will be around 30C during the day. HKO current readings at 07:00 HKT showed 27C at the Observatory, with thundery showers still possible.
   - Liquidity/practicality notes: PT-20260607-069 already holds 30C YES from 26c as a small hedge against PT-20260607-057 on 29C. No duplicate because quote conflict and one-decimal boundary risk remain meaningful.

4. NYC KLGA Jun 8 78-79F YES: maintained edge, heavily represented.
   - Current price: Polymarket readable pages show 78-79F around 30-38%, with 76-77F also heavily bid.
   - Implied probability: about 30-38%.
   - Estimated fair value: 40-48% YES.
   - Estimated edge: roughly +2 to +18 percentage points.
   - Confidence: Medium-low.
   - Key reasoning: NWS KLGA forecast still shows Monday sunny with a high near 78F and northeast wind 9-13 mph. That supports the 78-79F bucket, but 76-77F remains a real cap risk.
   - Liquidity/practicality notes: PT-20260607-061, PT-20260607-064, and PT-20260607-068 already cover the thesis. Do not add again unless a verified quote falls materially below 15c or station-specific evidence strengthens.

5. London EGLC Jun 8 19C YES: small maintained edge, source-conflicted.
   - Current price: Polymarket readable pages show 19C around 18-19%.
   - Implied probability: about 18-19%.
   - Estimated fair value: 24-34% YES.
   - Estimated edge: roughly +5 to +16 percentage points.
   - Confidence: Low to medium-low.
   - Key reasoning: Met Office daily card lists Monday maximum daytime temperature at 19C, but the hourly table peaks at 18C. This keeps 19C underpriced only if the daily max proves closer to settlement than the hourly trace.
   - Liquidity/practicality notes: PT-20260607-060 and PT-20260607-067 already represent this thesis. No duplicate unless a verified quote falls materially below 12c or station/hourly evidence strengthens.

## No-edge or downgraded markets

- Atlanta KATL Jun 8 80-81F YES is near fair after repricing. NWS shows high near 80F with showers and thunderstorms likely, while Polymarket has 80-81F leading around 39%. Maintain PT-20260607-065 only.
- Atlanta KATL Jun 8 78-79F YES remains tracking/hedged after official guidance shifted toward 80F.
- Chicago KORD Jun 8 82-83F YES is close to fair. NWS O'Hare-area guidance shows high near 83F with an 80% chance of showers/thunderstorms after early day; Polymarket has 82-83F around 35-40%. Existing PT-20260607-056 on 84-85F stays tracking/less favorable.
- Hong Kong Observatory Jun 8 29C YES remains open from 23c but is now cluster/tracking exposure after HKO centered the day around 30C.

## Recommended paper trades

No new paper-only positions were opened this run.

Maintained open paper positions only. The strongest edges are already represented, and current quote conflicts do not justify additional simulated exposure.

## Risks and invalidation factors

- Exact-bucket weather markets can flip on a one-degree station move or Wunderground rounding/final-history differences.
- Polymarket localized pages disagree on several current prices; executable quotes may differ from the browser-readable snapshots.
- Thunderstorms and cloud timing can cap Atlanta, Chicago, Hong Kong, and Miami below forecast-center buckets.
- Brief clearing or stronger insolation can push Hong Kong, Houston, Miami, or London one bucket warmer than expected.
- Existing paper exposure is concentrated in a few June 8 weather clusters, so duplicate sizing should stay conservative.

## Sources used

- Polymarket NYC Jun 8: https://polymarket.com/event/highest-temperature-in-nyc-on-june-8-2026
- NWS KLGA point forecast: https://forecast.weather.gov/MapClick.php?lat=40.77917&lon=-73.88
- Polymarket Hong Kong Jun 8: https://polymarket.com/event/highest-temperature-in-hong-kong-on-june-8-2026
- HKO 9-day forecast: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=fnd&lang=en
- HKO current readings: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=rhrread&lang=en
- HKO local forecast: https://data.weather.gov.hk/weatherAPI/opendata/weather.php?dataType=flw&lang=en
- Polymarket London Jun 8: https://polymarket.com/event/highest-temperature-in-london-on-june-8-2026
- Met Office London City Airport: https://weather.metoffice.gov.uk/forecast/u10j124jp
- Polymarket Houston Jun 8: https://polymarket.com/event/highest-temperature-in-houston-on-june-8-2026
- NWS KHOU point forecast: https://forecast.weather.gov/MapClick.php?lat=29.6454&lon=-95.2789
- Polymarket Atlanta Jun 8: https://polymarket.com/event/highest-temperature-in-atlanta-on-june-8-2026
- NWS KATL point forecast: https://forecast.weather.gov/MapClick.php?lat=33.6367&lon=-84.4281
- Polymarket Miami Jun 8: https://polymarket.com/event/highest-temperature-in-miami-on-june-8-2026
- NWS KMIA point forecast: https://forecast.weather.gov/MapClick.php?lat=25.78810&lon=-80.31690
- Polymarket Chicago Jun 8: https://polymarket.com/event/highest-temperature-in-chicago-on-june-8-2026
- NWS Chicago/O'Hare-area point forecast: https://forecast.weather.gov/MapClick.php?lat=41.8995&lon=-87.9403

## Repo log update

Updated odds/latest.md and paper_trading/paper_trade_summary.md. Created odds/history/2026-06-08T0012Z.md, alerts/2026-06-08T0012Z.md, data/market_snapshots/2026-06-08T0012Z.json, and paper_trading/maintenance/2026-06-08T0012Z.md. No new paper-trade entry was opened, and no real trades or betting actions were executed.
