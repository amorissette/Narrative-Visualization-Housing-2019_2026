# Boom, Freeze, and Lock-In: American Housing 2019-2026

CS 416 narrative visualization. An interactive slide show built with D3 and d3-annotation.

Live site: https://amorissette.github.io/cs416-narrative-viz/

Four scenes on the 2019-2026 U.S. housing market, using monthly
[Redfin Data Center](https://www.redfin.com/news/data-center/) metrics for 100 metro areas:

1. Prices rose 80% and stayed there (median sale price)
2. How fast homes sold: six weeks to 19 days, then back (median days on market)
3. Why prices did not fall: supply dried up (active listings)
4. Explore any metro and metric, with the national median for comparison

## Files

- `index.html` - the visualization
- `housing_data.csv` - Redfin monthly metro data, Jan 2019 to May 2026, 8,900 rows

## Running it locally

Serve the directory over HTTP so the CSV loads, for example `python -m http.server`,
then open http://localhost:8000/.

Only D3 v7 and d3-annotation are used, both from CDN.
