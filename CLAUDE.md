# KL Expat Guide

## Overview
Single-file HTML website (`index.html`) — a curated guide to festivals, Christmas markets, and cultural events near Kaiserslautern, Germany. For expats, military families, and travelers in the Rhineland-Pfalz region.

## Tech Stack
- Single-file HTML with embedded CSS and JavaScript
- Leaflet.js for interactive map (dark CARTO tiles)
- Google Fonts: Inter, Space Grotesk, Playfair Display, Source Sans 3
- No build tools, no framework — static HTML served via GitHub Pages

## Architecture
- **Dark hero section** with aurora background animation
- **Interactive Leaflet map** with festival (gold) and Christmas market (burgundy) markers
- **Festival Calendar** organized by month (Feb–Dec + Ongoing)
- **Christmas Markets** organized by country/region
- **Weekend Trip Ideas** — curated multi-stop itineraries
- **Mobile bottom tab bar** for Map/Coming Up/Festivals/Markets navigation
- **Filter system** — month pills + country pills + favorites toggle
- **Favorites** via localStorage star toggle
- **Click-to-zoom** — clicking event cards flies map to that location

## Content Stats (as of 2026-03-28)
- **100+ festivals** across 11 month sections (Feb–Dec + Ongoing)
- **41 Christmas markets** across 5 countries
- **5 countries**: DE, FR, BE, NL, LU
- Season: Feb–Dec 2026

## Key Cities Covered
- **Frankfurt**: Dippemess, Wäldchestag, Museumsuferfest, Opernplatzfest, Buchmesse, Apfelweinfest, Mainfest, Green Sauce Festival, IRONMAN, Nacht der Museen, Rheingauer Weinmarkt, Dippemess Autumn
- **Mainz**: Fastnacht (Big Three carnival), Johannisnacht, Open Ohr Festival, Rhein in Flammen, Weinmarkt (90th anniversary), FILMZ (25th anniversary)
- **Heidelberg**: Frühling, Schlossbeleuchtung (3x/year), Schlossfestspiele (100th anniversary), Stückemarkt, Herbst, Fastnachtsumzug, Enjoy Jazz
- **Mannheim**: Time Warp, Maimarkt, Stadtfest, Zeltfestival Rhein-Neckar, IFFMH Film Festival (75th), Fasnacht
- **Stuttgart**: Frühlingsfest, Weindorf (50th anniversary), Cannstatter Volksfest, jazzopen, Kessel Festival, Sommerfestival der Kulturen, Lange Nacht der Museen, BOSS OPEN

## Repo
- Remote: `https://github.com/djctwo/kl-expat-guide.git` (branch: main)
- Deployment: GitHub Pages (static)

## Status
- Live and functional
- Last major update: 2026-03-28 — added 37 new events across Frankfurt, Mainz, Heidelberg, Mannheim, Stuttgart
