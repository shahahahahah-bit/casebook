# Casebook

A field of case studies in urbanism and architecture, on a dark green ground.

Each square is one place. You can arrange the field three ways:

- **Place**: where each project is in the world, on ridgelines drawn from real elevation data
- **Theme**: gathered by main theme
- **Year**: along a timeline, with recent years given more room

Colours show each project's main theme, and soft shapes gather nearby projects that share one. Filter by theme, region, stage and year, search, or open the **Latest** and **Index** lists. Click a square to see its photo, facts and sources.

## Files

| File | What it is |
|---|---|
| `index.html` | The site: layout, styles and code |
| `data/casebook.json` | Every case study on the field: facts, position, stage, photo and sources |
| `data/elevation.bin` | World elevation at half-degree spacing (NOAA ETOPO1, public domain) |
| `data/skipped.json` | Posts the daily check decided not to add, with the reason (filled once daily updates start) |
| `casestudies.json` | The original research file for the 14 projects found in October 2026, with every link checked |

## Where the information comes from

- **Facts** come only from each project's article or its own website. No Wikipedia.
- **Positions** come from OpenStreetMap: at the exact site where the source names one, otherwise at the city centre (marked approximate).
- **Photos** are shown from the publishers' pages, with the photographer or owner credited under each one.
- **Sources** for new projects: [ArchDaily](https://www.archdaily.com/), [Dezeen](https://www.dezeen.com/), [Planetizen](https://www.planetizen.com/), [Urbanize Atlanta](https://atlanta.urbanize.city/) and [Urban Omnibus](https://urbanomnibus.net/).

## About saved changes

Case studies you add, edit or remove on the site are saved in your own browser only. Use **About → Export my changes** to keep a backup. To change what everyone sees, edit `data/casebook.json`.

## Viewing it locally

The page loads its data from `data/`, so open it through a small local web server rather than by double-clicking the file. For example, run `python3 -m http.server` in this folder and visit `http://localhost:8000`.
