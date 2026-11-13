# Growth Audit — Speech Blubs

**Live:** https://bterzic123.github.io/speechblubs-flow-rebuild/
**Prototype only:** https://bterzic123.github.io/speechblubs-flow-rebuild/?view=proto

Speech Blubs scores every child in onboarding, then shows every parent the same paywall. This audit rebuilds the screens between the score and the paywall in Speech Blubs' own design, at its published prices, as three clickable phones: one install from the milestone ad on Meta, one from a creator ad, one from the App Store.

## The five ideas

| # | Idea | Expected effect |
| :-- | :-- | :-- |
| 1 | Put the child's score and goals on the paywall ("Help Jane reach 92.3 in 4 months") | CR +15–20% to trial start |
| 2 | Ask for notifications after the trial starts, on your own reminder screen, not before welcome | CR +10–15% to trial start |
| 3 | Make "Calculating results…" read the answers back | CR +10–15% to trial start |
| 4 | Show the yearly plan you already sell (65,03 € a year, 5,42 € a month, save 67%) beside the trial | ARPU +10–15% |
| 5 | Bring Editors' Choice, the press row and one rating (4.6) to the paywall | CR +10–15% to trial start |

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps, not measured lift for Speech Blubs.

## Grounding

Screens, copy, illustrations and review quotes come from the Speech Blubs iOS app as recorded on 13 November 2026 on the Croatian App Store (16,59 € a month with a 7-day free trial). 65,03 € a year is the "Show of Support – Annual" plan on the same storefront's listing. 4.6 from 59K ratings, Editors' Choice and "Trusted by 10+ million parents" come from the US App Store listing. The ads come from the Meta Ad Library, Speech Blubs page, read on 13 November 2026. Jane's 71.2 and 92.3 are the values the app showed in the recording; Leo's and Mia's scores illustrate the same screen.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/.

Prepared by Adapty · [Book a demo](https://calendly.com/d/cty4-37z-zqj)
