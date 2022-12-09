# adventofcode
My solution for Advent of Code problems

# Completion
<!-- begin-year-badge -->
[![](https://img.shields.io/badge/2015-0%20stars-ef0f14)](./2015)
[![](https://img.shields.io/badge/2016-0%20stars-ef0f14)](./2016)
[![](https://img.shields.io/badge/2017-0%20stars-ef0f14)](./2017)
[![](https://img.shields.io/badge/2018-0%20stars-ef0f14)](./2018)
[![](https://img.shields.io/badge/2019-14%20stars-83551c)](./2019)
[![](https://img.shields.io/badge/2020-22%20stars-68671e)](./2020)
[![](https://img.shields.io/badge/2021-0%20stars-ef0f14)](./2021)
[![](https://img.shields.io/badge/2022-18%20stars-755e1d)](./2022)
<!-- end-year-badge -->

# Install

1. Get your AoC session cookie and put it in a `.env` (session=XXXXX)
2. Also set your email in `.env` to fill request headers
3. Install requirements using `pipenv install`

## Helpers
- `python src/prepare_year.py 2022`: Will create the directories for each day using the template in `year_template`
- `python src/download.py 1 2022`: Will download the input for problem1 of year 2022 (NB: You need to run `prepare_year`first)
- `python src/submit.py 3 1 2022`: Will submit solution for part 1 of day 3 of year 2022.

## Workflow
- When data become available, run the `src/download.py` script.
- Implement your solution in the `solve_part_1` and `solve_part_2` functions
- Use the `src/submit.py` CLI to submit any part once you are satisfied with it. You'll get any error message from AoC in the terminal.
