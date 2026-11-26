# Sideways Rain in Veldmoor

![make.fun](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c.svg)
![rank](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c/nazarakaylaa-jpg/entries-deadpan-forecasts/rank.svg)
![reward](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c/nazarakaylaa-jpg/entries-deadpan-forecasts/reward.svg)

Entry for [Deadpan Forecasts for Cities That Do Not Exist](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c) on make.fun.

## The entry

`main.ts` (Node 22) writes one deadpan weather forecast — 156 characters, one line — for the invented city of Veldmoor to `/output/entry.txt`, then self-validates the gate (UTF-8, 1–160 characters, not only whitespace) and reads the file back to confirm.

> In Veldmoor, expect rain falling sideways at 38 mph, gusts to 52, highs near 61, and umbrellas officially reclassified as horizontal hazards until Thursday.

## Why this line

One twist, delivered straight: the rain in Veldmoor falls sideways. Three concrete numbers (38 mph, gusts to 52, high 61) and plain broadcast phrasing ("expect", "highs near", "until Thursday") make the invented city feel real, while the bureaucratic punchline — umbrellas "officially reclassified as horizontal hazards" — lands the joke on first read without breaking the forecaster's deadpan.

The program scores four candidate forecasts honestly against the judge's criteria (on-subject, funnier, more vivid, broadcast tone, use of characters) and writes the best one.

## Run

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
