# GeoList

Map your HubSpot, Mailchimp, or Shopify contacts on an interactive map. Build geographic segments by drawing radius circles or selecting US states, then sync them back to your CRM as real lists you can use in campaigns.

[Learn More](https://info.optimizeme.today/applications/geolist) - [Read the deep-dive on the OptimizeMe blog](https://info.optimizeme.today/blog/how-to-plot-crm-contacts-on-a-map)

---

## The problem GeoList solves

HubSpot, Mailchimp, Shopify, and most other major CRMs collect address fields on every contact: city, state, ZIP, country. None of them will plot those contacts on a map.

You can filter "contacts in Texas" because that is a list query. You cannot answer "where are my customers" because that is a geographic question, and most CRMs are built around the contact record rather than the territory.

That gap shows up in:

- Event and roadshow planning
- Regional campaign targeting
- Field sales territory mapping
- Drive-time radius segmentation
- Identifying coverage gaps in your customer base

## What GeoList does

- Connects to HubSpot, Mailchimp, or Shopify in a few clicks
- Plots every contact based on the address fields already in your CRM
- Lets you draw a radius circle around any point and capture contacts inside
- Lets you shift-click US states to build regional segments
- Syncs the resulting segment back to your CRM as a real list
- Refreshes as your CRM updates, so audits stay accurate quarter over quarter

## Built with

- Flask (Python)
- Leaflet.js for the interactive map layer
- SQLite with persistent storage on Railway
- HubSpot, Mailchimp, and Shopify APIs

## Use cases

A marketing team planning a 12-city roadshow can pick the cities with their actual densest customer base rather than the ones picked from memory.

A field sales team can draw a 50-mile radius around each rep's office to see which accounts are reachable in a day, replacing a half-day Excel project with a 30-second answer.

An ecommerce brand can identify which metros are 40 percent of revenue and rebalance paid media spend accordingly instead of distributing budget evenly across markets that do not pull their weight.

## Learn more

- Product page: https://info.optimizeme.today/applications/geolist
- Deep-dive blog post on CRM map visualization: https://info.optimizeme.today/blog/how-to-plot-crm-contacts-on-a-map
- Made by Arturo Chinchilla at OptimizeMe: https://info.optimizeme.today/about/arturo-chinchilla

## About this repository

This is the public marketing repository for the GeoList SaaS product. The application source code is maintained privately. For product questions, feature requests, or partnership inquiries, contact us through the OptimizeMe site.
