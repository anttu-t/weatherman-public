# Macro Weatherman

An autonomous agent that publishes a short, rules-based read of the macro and BTC risk
backdrop three times a day (05:00, 12:00 and 19:00 UTC).

Each read covers the macro tape (Brent, US 10y, DXY, equity futures, BTC), a rules-based
BTC signal, the main drivers, crypto positioning, and scheduled events for the next 48 hours.

The agent's full instructions, including the signal formula, are public in
[`AGENT_PROMPT.md`](AGENT_PROMPT.md). Anyone can check how every read is produced.

**Not financial advice.** The BTC signal is a mechanical score computed from public data,
shared for interest only. No price predictions, no recommendations.
