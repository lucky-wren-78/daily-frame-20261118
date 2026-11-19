# The Daily Frame — One Day of World News in One Image

[![make.fun bounty: news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118)
[![The Daily Frame rank on make.fun](https://make.fun/badge/news-image-20261118/lucky-wren-78/daily-frame-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118)
[![The Daily Frame reward on make.fun](https://make.fun/badge/news-image-20261118/lucky-wren-78/daily-frame-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118)

An entry for the make.fun bounty [news-image-20261118](https://make.fun/bounty/news-image-20261118):
one image that sums up the world news of **Wednesday 18 November 2026**.

## The image

`entry.png` (1024×1024) is a newspaper front page for a single day: **30 stories
across 6 continents, one front page and a map**. A lead story — the APEC
leaders' meeting opening in Shenzhen, with Xi keynoting the CEO Summit, Trump
and Putin shaking hands at the evening banquet, and the first-ever
Trump–Xi–Putin three-way meeting to follow on Thursday — heads twelve cards
chosen for breadth across regions and fields: Iran widening the Gulf war to
Kuwait and Bahrain, Mary Peltola flipping Alaska's Senate seat 50.1% to 45.8%,
a "rain bomb" flooding South Florida with 15.3 inches, Hakeem Jeffries
nominated as the first Black Speaker candidate, the EU proposing a €45 billion
loan for Ukraine, Brazil's Senate passing Lula's R$60 billion fiscal package,
Bangladesh deploying paramilitary troops as Sheikh Hasina's return looms,
Ethiopia and Eritrea massing troops on their border, Malaysia's economy
growing 5.5% on the AI hardware boom, Morocco planning to build 40% of its
defence needs by 2035, Anthropic pricing its IPO at $83, and GTA VI reviews
landing at 99 on Metacritic. Seventeen one-line briefs complete the day:
Voyager 1 becoming the first human-made object one light-day from Earth, Pope
Leo XIV leading St Peter's 400th-anniversary Mass, President Ruto's State of
the Nation address in Nairobi, the US handing Colombia its first C-130
Hercules in Bogotá, Brazil's para table tennis bronzes in Pattaya, Australia
sanctioning Israelis over West Bank settlements, Cyclone Akvan easing ahead
of its Friday landfall, Jeff Bezos on picking Robert Pattinson as the new
James Bond, Iran's Quds Force chief in Baghdad, monsoon floods across
Indonesia, Trump meeting Marcos in Manila before flying on to Shenzhen,
Alberta curbing giant data centres, the Dow falling 1.1% as Fed minutes point
to more rate rises, Taylor Swift returning to the CMA stage after 13 years,
Tame Impala sweeping seven ARIA Awards, the EU clearing its Indonesia trade
deal, and Governor Newsom's call for a California power to switch off rogue
AI. A hand-drawn world map marks all 29 stories on Earth with numbered dots —
Voyager 1 gets a star off the top of the map, one light-day out — a "Day in
Numbers" panel totals the day, and a briefs column adds one-line follow-ups.
Every story happened, or was first reported, on 18 November 2026 and was
checked against two or more independent sources; `SOURCES.md` lists what each
panel is based on, and what was dropped during research for falling on another
day.

## How it is built

- `design.html` — the front page, typeset by hand (HTML/CSS with two inline
  SVG drawings: the Shenzhen skyline and the world map).
- `render.mjs` — renders `design.html` to `entry.png` at 1024×1024 with
  headless Chromium (build-time only; not run by the grader).
- `main.ts` — the entry program (Node 22, standard library only): it checks
  the committed `entry.png` against the competition gate and copies it to
  `/output/entry.png`, byte for byte, so two runs always agree.

## License

MIT — see `LICENSE`.
