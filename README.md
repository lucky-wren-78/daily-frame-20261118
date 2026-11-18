# The Daily Frame — One Day of World News in One Image

[![make.fun bounty: news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118)
[![The Daily Frame rank on make.fun](https://make.fun/badge/news-image-20261118/lucky-wren-78/daily-frame-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118)
[![The Daily Frame reward on make.fun](https://make.fun/badge/news-image-20261118/lucky-wren-78/daily-frame-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118)

An entry for the make.fun bounty [news-image-20261118](https://make.fun/bounty/news-image-20261118):
one image that sums up the world news of **Wednesday 18 November 2026**.

## The image

`entry.png` (1024×1024) is a newspaper front page for a single day: **13 stories
across 5 continents, one front page and a map**. A lead story — the APEC
leaders' meeting opening in Shenzhen, with a first Trump–Xi–Putin three-way
meeting to follow on Thursday — heads twelve cards chosen for breadth across
regions and fields: Kuwait intercepting hostile drones as the US–Iran exchange
widens, Australia sanctioning three Israelis and four organisations over West
Bank settlements, Voyager 1 becoming the first human-made object one light-day
from Earth, Severe Cyclone Akvan bearing down on India's Andhra coast, Jeff
Bezos on picking Robert Pattinson as the new James Bond, Iran's Quds Force
chief in Baghdad, monsoon floods across Indonesia, Pete Hegseth handing
Colombia its first Hercules C-130 in Bogotá, St Peter's Basilica at 400 years
since its dedication, President Ruto's State of the Nation address in Nairobi,
Brazil's para table tennis semi-finalists in Pattaya, and Trump meeting Marcos
in Manila before flying on to Shenzhen. A hand-drawn world map marks the
stories with numbered dots — Voyager 1 gets a star off the top of the map, one
light-day out — a "Day in Numbers" panel totals the day, and a wire ticker
adds one-line follow-ups. Every story happened, or was first reported, on
18 November 2026 and was checked against two or more independent sources;
`SOURCES.md` lists what each panel is based on, and what was dropped during
research for falling on another day.

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
