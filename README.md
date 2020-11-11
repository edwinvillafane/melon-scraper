# Melon Daily Chart Scraper

This is a self-updating repository of song positions on the Melon (Korean music streaming platform) Daily Chart.

## How it works

A script runs periodically to scrape the [24Hits Melon Chart](https://www.melon.com/chart/index.htm). That list of songs is sorted by chart position and then committed to this repository which is done via [GitHub Actions](https://docs.github.com/en/actions). 

## Getting the data

The most recent version of the data is contained in `melon-trends.json`. In order to see historical changes, you can click on the different commits to view the chart Top 100 songs on Melon during that hour.