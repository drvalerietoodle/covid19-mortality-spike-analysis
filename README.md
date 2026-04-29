# COVID-19 Mortality Data: When the Spike Isn’t the Story

COVID-19 mortality data is often treated as if it reflects real-time events. In practice, daily death counts can be shaped by reporting delays, batching, and revisions.

This project compares raw daily mortality counts with a smoothed trend to show how easily accurate data can be misinterpreted.

## Core Insight

> The number may be accurate, but the interpretation can still be wrong.

## What This Analysis Shows

- Raw daily death counts are highly volatile
- Sharp spikes may reflect reporting artifacts, not real-time mortality events
- A 7-day rolling average reveals a more stable underlying trend

## Why This Matters

Public health data influences decision-making, risk perception, and policy. Misinterpreting short-term fluctuations can lead to incorrect conclusions—even when the underlying data is correct.

## Data Source

New York Times COVID-19 U.S. dataset:  
https://github.com/nytimes/covid-19-data

## Tools

Python, pandas, matplotlib
