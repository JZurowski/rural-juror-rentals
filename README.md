# Rural Juror Rentals

A single-page DVD collection browser styled after a 90s Blockbuster video store.

## What's in the box

- **index.html** — the entire site, self-contained, no server or external data files required. Open it in any browser.

## Features

- **Three tabs** — Film, TV, and Other, matching the three sheets from the source spreadsheet
- **Live search** — filters titles as you type, matching against title, genre, and collection note
- **Genre filter** — dropdown populated from every genre tag in the collection
- **Cards** — each item displays Title, Year, Genre, and Collection/Note
- **Card modal** — click any card to open a full-screen overlay with all details; click outside or press Escape to close
- **Popcorn burst** — clicking a card triggers animated popcorn kernels that arc outward from the card in all directions before fading

## Data

All 266 titles are baked directly into the HTML as a JavaScript array — no `.json`, no fetch, no dependencies beyond a Google Fonts import. The three source tabs from `Jordan Film & TV Database.xlsx` map to the Film, TV, and Other tabs respectively.

## Design

Inspired by the Blockbuster Video store aesthetic: royal blue and gold palette, **Bangers** display font for titles, **Anton** for labels, and a chunky membership-card card style throughout.
