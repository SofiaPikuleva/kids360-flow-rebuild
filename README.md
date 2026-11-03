# Growth Audit — Kids360

**Live:** https://sofiapikuleva.github.io/kids360-flow-rebuild/

Five ranked ideas for Parental Control App Kids360, plus a clickable prototype of the onboarding and paywall rebuilt in Kids360's own design. Prepared by Adapty, November 2026, from the live iOS flow and the App Store listing.

## The five ideas

| # | Idea | Screen | Potential outcome |
| :-- | :-- | :-- | :-- |
| 01 | Open the paywall on the goals they picked | Paywall | CR +15–20% |
| 02 | Ask once, then show only what they picked | Goals, Your features | CR +10–15% |
| 03 | Let the loader set up what they asked for | Loader | CR +10–15% |
| 04 | One proof number — the one on your store page | Welcome, Paywall | CR +10–15% |
| 05 | On close, show how the 3-day trial works | Offer on close | CR +5–10% |

Every screen in the prototype is Kids360's own design. Only the order and a few lines changed, using things the app already shows or owns.

## Grounding

Every price and claim comes from Kids360's own published material: the US App Store listing (4.6 from 9K ratings; screen time limits, app blocking, schedules, web filtering, GPS location) and the in-app screens (the six goals, the feature slides, the 2.5x survey line, the Linda Barnes review, the paywall with USD 39.99 a year and USD 6.99 a month, and the 3-day free trial on the “Don't leave yet” sheet).

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for Kids360.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?open=proto` to open straight on the prototype.
