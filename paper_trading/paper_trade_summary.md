# Paper Trade Summary

This file tracks simulated paper positions only. It is not a record of real bets or trades.

## Current focus

- 2026-06-07 23:12 UTC run: opened PT-20260607-068 on NYC KLGA Jun 8 78-79F YES at 18c, $15 simulated notional. This is a tiny third same-thesis add-on because the verified quote moved below the prior below-20c trigger while NWS KLGA still shows Monday high near 78F. Do not add NYC again unless a verified quote falls materially below 15c or station-specific evidence strengthens.
- 2026-06-07 23:12 UTC run: opened PT-20260607-069 on Hong Kong Observatory Jun 8 30C YES at 26c, $15 simulated notional. Treat this as an adjacent-bucket hedge against PT-20260607-057 on 29C after HKO shifted the forecast max to 30C. Do not duplicate the 29C/30C cluster unless a clean quote and nowcast materially improve.
- London EGLC Jun 8 19C YES remains represented by PT-20260607-060 and PT-20260607-067; current 16c remains positive but is above the sub-12c add trigger and hourly guidance still peaks at 18C.
- Houston KHOU Jun 8 88-89F YES is now mostly converged around 39c versus fair 42-52%; maintain PT-20260607-059 only.
- Atlanta KATL 80-81F, Miami KMIA 90-91F, and Chicago KORD 82-83F are near fair after repricing; maintain existing paper positions only.

## Current lessons

- Do not duplicate existing exact-bucket paper entries unless the verified price improves materially or the station-specific signal strengthens.
- A same-thesis edge can still rank highly while being a no-add because the paper book already represents it.
- Treat tabular/hourly guidance as a sanity check when a rounded daily high leaves adjacent exact buckets live.
- Track overlapping station/date clusters carefully, especially NYC, Chicago, Houston, Miami, London, and Hong Kong where exact-bucket boundaries are tight.
- A small price improvement is not enough for an add-on when visible volume is thin or localized pages conflict.
- When an official forecast shifts by one bucket, prefer a small adjacent-bucket hedge over adding to the older thesis.
- Third same-thesis add-ons should be tiny by default even when a trigger is met.
