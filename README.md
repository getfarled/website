# Farled website

Product site for [Farled](https://github.com/getfarled/farled) — safe routing
for AI-assisted engineering.

**Zero toolchain**: plain HTML + CSS (+ ~10 lines of vanilla JS for scroll
reveals). Deploy anywhere that serves static files — GitHub Pages, Vercel,
Netlify, or `python3 -m http.server`.

## Design notes

The visual system is a **daylight nautical chart** — the product is named
after one (*farled*, Swedish: a marked safe channel). Deep water is white,
shallows are blue, the ink is navy; buoys mark the channel: starboard green
for open source, port red for collisions, gold for chartered deep water
(Cloud). Type: Newsreader (engraved water-label display), Instrument Sans
(body), Spline Sans Mono (soundings, code). The page itself is framed as a
chart sheet — neatlines with graduation ticks, sections labeled as chart
NOTES, and a hero chart that plots two git branches as converging shipping
lanes with the collision marked.

All feature claims correspond to shipped, tested code in
`getfarled/farled` and `farled-cloud/farled-cloud`; the terminal transcript
is real `farled demo collision` output.

## Preview locally

```sh
python3 -m http.server -d . 8080
# → http://localhost:8080
```
