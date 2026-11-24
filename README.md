[README.md](https://github.com/user-attachments/files/35336126/README.md)
# Market Entry Desk v2 · MG2644 coursework toolkit

One web page with four tools. Each tool is linked to a section of the coursework, and an essay map ticks off each part as students finish it. The game rounds have been removed.

## Publish (same link as before)

Upload this `index.html` to your `market-entry-desk` GitHub repository, replacing the old one. GitHub Pages updates in 1–2 minutes at https://mj-kim2.github.io/market-entry-desk/

## What's on the page

| # | Tool | Students do | Feeds |
| --- | --- | --- | --- |
| 0 | Set-up | Company, product, home, host, currencies | — |
| 1 | Currency Lab | Four animated labs: PPP basket, IFE savings race, Fisher bars, forecast fan. Each lab: watch → play → my numbers → quick check → essay link | Economic Environment; Recommendations |
| 2 | Excel checker | Copy in Seminar 3 numbers; each formula is checked from their own inputs. Spots ATOM's template numbers automatically | Economic Environment |
| 3 | Governance heat map | Host vs home, any year 2017–2025, play through the years, click a row for range bars and a trend line, "spot the risk" check, choose one political + one legal indicator, draft paragraphs, download the figure | Political, Legal & Cultural |
| 4 | Essay tables | Three tables + Harvard reference list, copy to Word or download as images | All sections |

**Essay map** (right-hand panel; at the bottom on phones): 14 items across Economic Environment, Political/Legal, Recommendations and References. It ticks green as students finish, and offers a "coursework checklist" download with their numbers and draft paragraphs.

## Decisions built in

- **Heat map grouping:** Political = voice & accountability, political stability, government effectiveness. Legal = regulatory quality, rule of law, control of corruption.
- **Colours:** one colour scale, darker = weaker score = more risk, in bands of 20. Colour-blind safe and prints in grey.
- **Culture:** not in the heat map. The page tells students to use a cultural source (Hofstede/The Culture Factor, GLOBE).
- **The heat map figure** is labelled "Figure made by the author with the MG2644 module tool", and the page says it is extra to the two required Excel figures.
- **ATOM** appears only through the lecturer link at the bottom of the welcome page.

## Save files

- Week 8 save files and save codes still load. The company, countries and Excel numbers carry over, and the old round choices are ignored.
- An ATOM save shows a red banner with "Set up my own company".
- Work also saves in the browser automatically. Students should still download the save file to OneDrive.

## Data

- **World Bank Worldwide Governance Indicators:** your download, updated 25 September 2026, covering 2017–2025 with 90% ranges for 216 economies.
- **Gaps:** French Polynesia and New Caledonia have no score for two indicators, so students type those in (marked *).

## Facts used in the labs

- **Brazil 2020:** +33.3% reais per euro (yearly average), from the Seminar 3 file. PPP uses the inflation that really happened in 2020: 3.2% (World Bank) vs about 0% in Italy, and the lab now says so. IFE uses rates at the start of 2020: Selic 4.5% (Dec 2019); ECB deposit rate −0.5%.
- **Türkiye, Oct 2022:** inflation 85.5%, policy rate 10.5% (Reuters); the lira lost about 29% in 2022.
- **Argentina, Dec 2023:** official rate 366.5 → 800 pesos per US dollar (Bloomberg).
- **Egypt, 6 Mar 2024:** 30.85 → about 50 pounds per US dollar (CNBC).
- **Argentina 2023 inflation of 211%** (Lab 1 preset): 211.4% for the year to December 2023 (INDEC, reported by Reuters, 11 January 2024).

## Fixes in v2.1 (24 November 2026)

- **Saved work with empty cells:** after a reload or a Week 8 save file, empty Excel cells showed the word "null", counted as 0, and could give false ticks and wrong numbers in the checklist. Empty cells now stay empty.
- **Labs with long currency names or large numbers** (e.g. "Vietnamese dong", rupiah): text no longer runs out of the boxes in Labs 1 and 2.
- **Host currency getting stronger** (e.g. host inflation lower than home): Lab 1's dial can now show "host stronger"; Lab 1, Lab 2 and Lab 4 wording is correct for negative PPP/IFE numbers; Lab 4's price range is shown low to high.
- **Lab 3:** bars work with deflation or a negative interest rate; labels no longer overlap; the Türkiye sentence only appears on the Türkiye example.
- **Lab 4:** PPP and IFE labels no longer overlap when close; "Brazil, 2020" button to go back to the first example; Labs 3 and 4 scroll to the chart after "my numbers".
- **Heat map:** the range-bar year updates when the year changes; the Play button no longer gets stuck on "Playing…"; changing host or home here now shows a warning (it changes the whole toolkit, and the currency name and Excel numbers stay the old ones); the PNG keeps the * for typed scores; the look-up link goes to the WGI data page.
- **Citations:** heat-map facts and figure notes now cite "World Bank (2026b)", matching the reference list.
- **Text:** removed "company card" (from the old game); the Week 8 game rule now says "If you played the Week 8 game…".
- **Phones:** the Excel checker and essay tables no longer run wider than the screen.

## Tested

- Full run of every tool in Chrome at desktop (1366 px) and phone (390 px) size, with no console errors.
- Real Week 8 save files (own company, ATOM, own company with ATOM's numbers) and a save code, made with the Week 8 version from the repository history.
- Reload with a half-finished Excel checker; deflation; a negative policy rate; a host currency that gets stronger; a home currency much weaker than the host; a missing-data country (French Polynesia); all downloads.
- Animations respect "reduce motion" settings.
