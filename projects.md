---
layout: default
title: Selected Projects
---

## EV Charging Data Platform (Private)

- **Focus**: OCPI normalisation, analytics
- **Tech**: Databricks, Power BI, Python
- **Why it matters**: Enabled cross‑CPO reporting
- **Learnings**: Timezone handling, 

## Collecting PCPR Open Data for Public Charge Points (Public)

- **Focus**: OCPI Data Collection
- **Tech**: Python, Cloudflare Workers, OCPI Authorisation, GeoJSON, QGIS
- **Why it matters**: Since UK government stopped collating a central source and outsourced to ZapMap who charge to access the collated data, it's become much harder to collect the open data, where published.
- **Learnings**: Most CPOs use a "simple OCPI" mostly via one provder which makes sign-up easy (when you can find their sign-up link, or guess) Shout out to the Techs at instagram for their support in getting the project working with their "proper" OCPI implementation requiring A-B-C token exchange, which brought to life the dry OCPI spec

## Location Weather

- **Focus**: Open Data Collation for a given location
- **Tech**: Cloudflare Worker, Wrangler, MetOffice API
- **Why it matters**: It Doesn't, but I could have the display as I wanted it for my use case
- **Learnings**: Dark/Light mode handling isn't trivial when working in iframes

## Trent Levls (Private)

- **Focus**: Open Data Collation for a given location
- **Tech**: Cloudflare Worker, Wrangler,Durable Objects caching, Environment Agency API
- **Why it matters**: Wanted multiple locations on one display, and history for my use case
- **Learnings**: Internal/external location ID handling, weather stations and river monitoring don't line up too well


[View on GitHub](https://github.com/RennieDB?tab=repositories)