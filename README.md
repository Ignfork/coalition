# Coalition ($COALITION)

Single-file site: `index.html` (no build step, no folders). Deploy as-is on Vercel or GitHub Pages.

## Set your links
Near the top of the script in `index.html`:

```js
var CONFIG={xUrl:'',xHandle:'',ca:'',buyUrl:''};
```

## Data
- Trades are real public STOCK Act Periodic Transaction Reports (Aug-Oct 2026) as compiled by
  Trade With Congress (tradewithcongress.org), Glasshouse (tryglasshouse.ai) and Stock Alarm (stockalarm.io).
  Amounts are the ranges members report. Verify at disclosures-clerk.house.gov and efdsearch.senate.gov.
- To add filings, append rows to the `F` array: [member, ticker, asset, side B/S/P, traded MM-DD, filed MM-DD, range index, source].
- To add members, add to `MEM` with their bioguide ID.

## Photos
- Official congressional portraits (public domain, U.S. government works), loaded from
  unitedstates.github.io/images (fallback: bioguide.congress.gov). If both fail, the card shows initials.

## Calls
- Copy/Fade calls, baskets and the watchlist are saved in the visitor's browser in this preview.
  Scoring against an on-chain price oracle and the reward pool are planned for launch.
- The callers leaderboard handles are samples.

## Disclaimers on the page
- Not affiliated with or endorsed by any member of Congress. $NAME labels are labels, not tokens.
