---
title: "Problem Statement"
subtitle: "Final Project"
filters:
  - _resources/scripts/shortcodes.lua
standalone: true
self-contained: true
format:
  html:
    theme:
      - litera
      - _resources/templates/notebook-theme.scss
    toc: true # turn table of contents on/off
    toc-title: Contents
    anchor-sections: true
---

## About the data

Source: [Ultra Running on TidyTuesday](https://github.com/rfordatascience/tidytuesday/tree/master/data/2021/2021-10-26)

This dataset collects 5,010,730 results from 15,451 ultra running events from the last 23 years, making this the largest study ever done on the sport. It contains both race details such as distance, elevation changes, and results, and runner details such as age, gender, and nationality. 

## Possible questions

- Who was the fastest overall ultra runner of the time period this data covers?
  - Also broken down by race distance, or participant categories
- Have race times changed substantially over the years as the sport has progressed?
  - I.e. slowest now vs. slowest 10-20 years ago
- Have participation numbers in the sport changed over the years?
  - Is race popularity effected by race locations / dates / distances?
- Have age/gender/nationality demographics for ultra running changed over the years?
- How does runner nationality vs. race location effect times?
- How could any of the above be visualised?

## Possible models

- Can a time for a given distance be predicted from a model trained on a runners age/gender/nationality?
  - How about based on their previous results? Or a combination?
- Can participant numbers for a race be estimated given its location, distance, and elevation changes

---

**Project Navigation:**

[EDA Brief ▸](01-EDA-Brief.html)