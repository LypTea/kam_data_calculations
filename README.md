# kam_data_calculations

## What is this for?
These are graphs created to analyze data for the game Squad, requested by Kam in exchange for fumo :)

## Graphs
- [x] win_rate
- [x] levels played per month ( variable time period input is good here too, so you can look weekly etc)
- [x] Modes played per month (same as level but with mode)
- [x] number of mode/layer/level per bucket of winner tickets (under 100, 101-150, 151-200, 200+)
- [x] average winner tickets for each mode/layer/level

## How to run this?
- Have python3.11 installed ( used python3.11 for this, not sure if other versions work)
- Run commands below in an administator terminal:

```
python3 -m pip install pandas
python3 -m pip install numpy
```

- Afterwards, run `python3 -m notebook` in this directory
  - Alternatively, you can use VSCode with Jupyter extension and it will work fine.

## Notes on graphs
- Some graphs that looked disgusting were excluded (namely dividing by layer, there are way too many to make a sensible looking graph).
- The 'per month' graphs look weird but only because there is not enough data.