# awesome-berlinwahl-2026 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

##### Curated list of official datasets, maps, timelines, and reference material for the Berlin 2026 Abgeordnetenhaus and BVV elections.

This repository follows the same markdown layout as `awesome-berlin-data`, but is intentionally narrowed to the election for the 20th Abgeordnetenhaus of Berlin and the Bezirksverordnetenversammlungen on 20 September 2026.

Have something to add or change? Open a pull request or issue.

------------------------------

### Table of Contents

- [Election Basics](#election-basics)
- [Geometries & Boundaries](#geometries--boundaries)
- [Pre-Election & Structural Data](#pre-election--structural-data)
- [Rules, Deadlines & Candidacies](#rules-deadlines--candidacies)
- [Party Programs & Positions](#party-programs--positions)
- [Voter Information](#voter-information)
- [Election Operations & Context](#election-operations--context)

------------------------------

## Election Basics

Primary official entry points for the Berlin elections on 20 September 2026, plus one secondary background reference.

- 🗳️ [Berliner Wahlen 2026](https://www.berlin.de/wahlen/wahlen/berliner-wahlen-2026/) - Central overview from the Landeswahlleiter covering election information, candidate submissions, FAQs, boundary information, and voting rights for EU citizens.
- 📊 [Abgeordnetenhaus und Bezirksverordnetenversammlungen](https://www.statistik-berlin-brandenburg.de/abgeordnetenhauswahlen-bvv-berlin/) - Official statistics portal from Amt fur Statistik Berlin-Brandenburg with the 2026 election section, historical results, precinct-level result references, structural data, and links to maps and the Berlin Open Data portal.
- 📅 [Allgemeine Informationen](https://www.berlin.de/wahlen/wahlen/berliner-wahlen-2026/allgemeine-informationen/artikel.1578239.php) - Confirms the election date of 20 September 2026, links the official timeline PDF, and notes that around 2.4 million election notifications will be delivered between mid-August and 30 August 2026.
- 🏛️ [Senat legt Anzahl der Wahlkreise in den Bezirken und den Wahltag fur die Wahl zum Abgeordnetenhaus 2026 fest](https://www.berlin.de/rbmskzl/aktuelles/pressemitteilungen/2025/pressemitteilung.1566261.php) - Senate press release from 3 June 2025 fixing the election date and the distribution of Berlin's 78 constituencies across the 12 districts.
- 📚 [Wahl zum Abgeordnetenhaus von Berlin 2026](https://de.wikipedia.org/wiki/Wahl_zum_Abgeordnetenhaus_von_Berlin_2026) - Wikipedia overview page with background context, timeline notes, and linked references; useful as a secondary summary, but not an official source.

------------------------------

## Geometries & Boundaries

Official spatial datasets from Berlin Open Data, plus one official boundary reference page.

- 🗺️ [Geometrien der Wahlbezirke fur die Wahl zum 20. Abgeordnetenhaus von Berlin und BVV 2026](https://daten.berlin.de/datensaetze/geometrien-der-wahlbezirke-fur-die-wahl-zum-20-abgeordnetenhaus-von-berlin-und-bvv-2026) - Berlin Open Data dataset, published on 22 April 2026, with polygon geometries for the 2026 polling districts used for the Abgeordnetenhaus and BVV elections.
- 📐 [Geometrien der Wahlkreise fur die Wahl zum 20. Abgeordnetenhaus von Berlin 2026](https://daten.berlin.de/datensaetze/geometrien-der-wahlkreise-fur-die-wahl-zum-20-abgeordnetenhaus-von-berlin-2026) - Berlin Open Data dataset for the 78 Abgeordnetenhaus constituencies, first published on 22 October 2025 and updated on 16 April 2026 with minor topological adjustments.
- 🌐 [Wahlgebiete fur die Wahl zum 20. Abgeordnetenhaus von Berlin 2026 - WMS](https://daten.berlin.de/datensaetze/wahlgebiete-fur-die-wahl-zum-20-abgeordnetenhaus-von-berlin-2026-wms-8e5cac56) - Berlin Open Data WMS map service from Amt fur Statistik Berlin-Brandenburg, published on 22 April 2026, covering the 2026 election areas (constituencies plus polling and postal-vote districts); service endpoint at `https://gdi.berlin.de/services/wms/wahlgebiete_agh2026`, licensed CC BY 3.0 DE.
- 🔷 [Wahlgebiete fur die Wahl zum 20. Abgeordnetenhaus von Berlin 2026 - WFS](https://daten.berlin.de/datensaetze/wahlgebiete-fur-die-wahl-zum-20-abgeordnetenhaus-von-berlin-2026-wfs-bc61142d) - Companion WFS service for the same election areas, providing the vector features directly for GIS use and automated download.
- 🗾 [Darstellung der Wahlgebiete im Geoportal Berlin](https://gdi.berlin.de/view/wahlgebiete_agh2026) - Interactive Geoportal map viewer for the 2026 election areas with three layers: `agh2026_awk` (constituencies), `agh2026_uwb` (polling districts), and `agh2026_bwb` (postal-vote districts); note the underlying data status is 22 April 2026, the Geoportal publication followed on 16 July 2026.
- 🖼️ [Wahlkreiskarten 2026](https://www.statistik-berlin-brandenburg.de/wahlkreiskarten-2026) - Official map page with district overview maps, individual PDF maps for all 78 constituencies, and PDF address directories listing the addresses belonging to each polling district.
- 🧭 [Wahlgebietseinteilung](https://www.berlin.de/wahlen/wahlen/berliner-wahlen-2026/wahlgebietseinteilung/artikel.1600253.php) - Official page explaining the 78 constituencies, their distribution by district, links to district-level constituency maps, and the Open Data geometry download.

------------------------------

## Pre-Election & Structural Data

Official pre-election statistics from Amt fur Statistik Berlin-Brandenburg, published in June 2026, including earlier election results recalculated onto the 2026 boundaries.

- 📕 [Vorwahldaten, Strukturdaten - Bericht (PDF)](https://download.statistik-berlin-brandenburg.de/4ab89f5e666a3418/0d89fa32f60b/SB_B07-02-01_2026j05_BE.pdf) - 32-page official statistical report for the 20 September 2026 elections with the 2023 Abgeordnetenhaus and 2025 Bundestag results recalculated onto the new 2026 constituencies, plus eligible voters by age and sex, citizenship, migration background, and social-structure data by district and constituency.
- 📗 [Vorwahldaten, Strukturdaten - Tabellen (XLSX)](https://download.statistik-berlin-brandenburg.de/dce8788111faf339/5cad9dd74f0a/SB_B07-02-01_2026j05_BE.xlsx) - Machine-readable companion tables to the Vorwahldaten report.
- 🔢 [Abgeordnetenhauswahl 2023, Zweitstimmen umgerechnet auf die Wahlgebiete 2026 (XLSX)](https://download.statistik-berlin-brandenburg.de/eddea71cdf4e6f2b/291e0923b0a7/DL_BE_AGH2026_AGH2023.xlsx) - 2023 second-vote results recalculated onto the 2026 election areas; removes the need to spatially reaggregate old results onto the new boundaries yourself.
- 🔢 [Bundestagswahl 2025, Zweitstimmen umgerechnet auf die Wahlgebiete 2026 (XLSX)](https://download.statistik-berlin-brandenburg.de/1e70272a9cea4ac4/0cf516026bf3/DL_BE_AGH2026_BT2025.xlsx) - 2025 federal-election second-vote results recalculated onto the 2026 election areas.
- 🧮 [Strukturdaten auf Wahlbezirksebene (XLSX)](https://download.statistik-berlin-brandenburg.de/aa56eddd2ea25921/1dd6f94397c4/DL_BE_AH2026_Strukturdaten.xlsx) - Demographic and social-structure data at polling-district level, the finest granularity available; well suited for small-area analysis and election models when joined with the polling-district geometries.

------------------------------

## Rules, Deadlines & Candidacies

Official sources for candidate submissions, formal requirements, and key legal deadlines.

- 📝 [Wahlvorschlage](https://www.berlin.de/wahlen/wahlen/berliner-wahlen-2026/wahlvorschlaege/artikel.1600254.php) - Main page for parties and candidates with deadlines for participation notices, candidate submissions, support signatures, downloadable forms, and procedural guidance.
- ⏱️ [Terminplan fur die Berliner Wahlen 2026](https://www.berlin.de/wahlen/wahlen/berliner-wahlen-2026/allgemeine-informationen/terminplan.pdf) - Two-page official PDF with the binding timeline, including 20 May 2026 for participation notices and 14 July 2026 for submission of candidate documents.
- 📘 [Aufruf zur Einreichung der Wahlbeteiligungsanzeige und Wahlvorschlage fur die Berliner Wahlen 2026](https://www.berlin.de/wahlen/wahlen/berliner-wahlen-2026/wahlvorschlaege/wahlaufruf-abgh_bvv-2026.pdf) - Detailed official call for submissions with legal references, procedural explanations, and candidacy requirements.
------------------------------

## Party Programs & Positions

Programs of the parties running with a Landesliste for the 2026 Berlin election. Entries are grouped by source status: final adopted 2026 Wahlprogramm vs. other official program material. All links verified on 26 July 2026.

### Final 2026 Wahlprogramme

- 🟢 [Grune Berlin: Unser Wahlprogramm fur 2026](https://gruene.berlin/wahlprogramm) - Final program page with the slogan `Politik andern, Berlin bleiben`; the site states the Landesdelegiertenkonferenz adopted the program on 14 and 15 February 2026. Direct downloads: [Wahlprogramm (PDF)](https://gruene.berlin/fileadmin/BE/lv_berlin/files/Wahlprogramm_2026_Online.pdf), [Leichte Sprache (PDF)](https://gruene.berlin/fileadmin/BE/lv_berlin/files/Wahlprogramm_2026_Leichte_Sprache_Online.pdf).
- 🔴 [Die Linke Berlin: Wahlprogramm](https://dielinke.berlin/partei/wahlen/abgeordnetenhauswahlen-2026/wahlprogramm/) - Final program `Berlin bezahlbar machen`, adopted by the Landesparteitag on 25 April 2026 and published chapter by chapter on the official program page.
- 🟣 [BSW Berlin: Wahlprogramm AGH-Wahl 2026](https://bsw.berlin/allgemein/entwurf-des-landeswahlprogramms-des-berliner-bsw/) - Official program page with the full PDF `Mit uns endlich vernunftig und gerecht`, adopted by the Landesparteitag on 25 April 2026; note the URL still carries the old `entwurf` slug even though the page presents the adopted program. Direct download: [Wahlprogramm (PDF)](https://bsw.berlin/wp-content/uploads/Wahlprogramm-BSW-Berlin-AGH-Wahl-2026.pdf) - 66 pages.
- 🟡 [FDP Berlin: Wahlprogramm zur Abgeordnetenhauswahl 2026](https://www.fdp-berlin.de/wahlprogramm) - Final program page with the full PDF under the slogan `Fur die Freiheit`, adopted as a Landesparteitag resolution and also listed in the party's official Beschlussdatenbank. Direct download: [Wahlprogramm (PDF)](https://www.fdp-berlin.de/sites/default/files/2026-07/Wahlprogramm_FDP%20Berlin_Abgeordnetenhauswahl%202026_FINAL.pdf).
- ⚫ [CDU Berlin: Wofur wir stehen - Regierungsprogramm 2026-2031](https://cdu.berlin/wofuer-wir-stehen) - Official program page with the downloadable `Regierungsprogramm 2026-2031`, adopted by the 50. Landesparteitag on 9 June 2026.
- 🔴 [SPD Berlin: Wieder Berlin - unser Wahlprogramm](https://spd.berlin/wahlprogramm/) - Final program `Wieder Berlin`, adopted unanimously by the Landesparteitag on 9 May 2026; the page offers a PDF download, an e-book version, and per-topic subpages.
- 🔵 [AfD Berlin: Wahlprogramm Berlin 2026 (PDF)](https://lichtenberg.afd.berlin/wp-content/uploads/2026/07/AfD-WK-Berlin-Wahlprogramm-Webversion.pdf) - 99-page final program, adopted by the Landesparteitag in the Stahlpalast in Brandenburg an der Havel; no dedicated program page on the state association's main site as of July 2026, the PDF is hosted on the Lichtenberg district site.
- 🟤 [DKP Berlin: Wahlprogramm](https://berlin.dkp.de/berliner-wahlen/) - Program page for the Berlin elections with the [Wahlprogramm (PDF)](https://berlin.dkp.de/wp-content/uploads/sites/83/2026/04/Wahlprogramm.pdf) - 8 pages.
- 🃏 [Die PARTEI Berlin: Wahlprogramm zur AGH-Wahl 2026](https://die-partei-berlin.de/archiv/7778) - Satirical ten-point plan, published as a web page only, no PDF.
- 🐾 [Tierschutzpartei: Wahlprogramm AGH 2026](https://www.tierschutzpartei.de/wahlprogramm-agh26/) - Program presentation page with the [Wahlprogramm (PDF)](https://www.tierschutzpartei.de/wp-content/uploads/2026/06/Wahlprogramm_AGH_26.pdf) - 96 pages across 26 topic areas.
- 🟪 [Volt Berlin: Programm zur Abgeordnetenhauswahl 2026](https://voltdeutschland.org/berlin/programm/programme/programm-berlin-2026) - Program page with the [Wahlprogramm (PDF)](https://voltdeutschland.org/storage/assets-berlin/pdf/policy-wahlprogramm-2026/2026_ber_wahlprogramm.pdf) plus a short version on the page.

### No final 2026 Wahlprogramm yet (as of 26 July 2026)

- 🎤 [Die Urbane: Parteiprogramm](https://www.die-urbane.de/programm.html) - General party program, described by the party itself as an incomplete work in progress; no separate Berlin 2026 Wahlprogramm found.
- 🍊 [ODP Berlin: Abgeordnetenhauswahl 2026](https://www.oedp-berlin.de/wahlen/abgeordnetenhauswahl-2026) - Official 2026 election page, which so far points to the existing [Landesprogramm Berlin (PDF)](https://www.oedp-berlin.de/fileadmin/user_upload/01-instanzen/02/030-Programm/Landesprogramm-Berlin.pdf) instead of a dedicated 2026 Wahlprogramm.
- ⚙️ [Partei des Fortschritts: Wahl zum Abgeordnetenhaus Berlin 2026](https://partei-des-fortschritts.de/wahl-zum-abgeordnetenhaus-berlin/) - Official election page stating `Unser Wahlprogramm kommt bald`; until then only the [Grundsatzprogramm (PDF)](https://partei-des-fortschritts.de/wp-content/uploads/2026/01/260108_PdF_GrundsatzProgramm.pdf) is available. Worth re-checking regularly.
- ☭ [SGP: Wahlaufruf `Berlinwahl 2026: Sozialismus statt Krieg`](https://www.wsws.org/de/articles/2026/07/10/sgpb-j10.html) - Wahlaufruf published on wsws.org, currently the most detailed Berlin program statement of the party; no separate Wahlprogramm or PDF found.

------------------------------

## Voter Information

Resources for eligibility, polling-place lookup, brief voting, and voter-facing convenience tools.

- ❓ [Frage- und Antwortkatalog](https://www.berlin.de/wahlen/wahlen/berliner-wahlen-2026/fragen-und-antwortkatalog/artikel.1646712.php) - Official FAQ explaining major 2026 changes, including voting eligibility from age 16 for the Abgeordnetenhaus election and the new single ballot combining first and second vote.
- ✉️ [Allgemeine Informationen](https://www.berlin.de/wahlen/wahlen/berliner-wahlen-2026/allgemeine-informationen/artikel.1578239.php) - Reference page for election notifications, timeline downloads, and general administrative information for voters.
- 📍 [Wahllokalsuche](https://www.berlin.de/wahlen/wahlen/berliner-wahlen-2026/fragen-und-antwortkatalog/artikel.1646712.php) - Announced by the Landeswahlleiter as available from 10 August 2026 after election notifications are issued; not active yet, so this link currently points to the official FAQ source that describes the service.
- ✉️ [Wahlbrief](https://wahlbrief.de/) - Unofficial open-source service by FragDenStaat that helps users generate and send a brief voting request by email; useful as a convenience tool, but not an official Berlin election site.
- 🤖 [wahl.chat](https://wahl.chat/landtagswahl-rheinland-pfalz-2026) - AI-based election information tool currently published for other 2026 state elections; Berlin is not included yet, so this link is only a reference to the existing product, not an active Berlin resource.
- 🧭 Wahl-O-Mat fur Berlin 2026 (coming soon) - Placeholder for the expected pre-election comparison tool; intentionally left without a link until the official 2026 version is published.

------------------------------

## Election Operations & Context

Operational context around how the election is being prepared and staffed.

- 👥 [Informationen fur den Wahlvorstand](https://www.berlin.de/wahlen/organisation/wahlhelfende/) - Official page for election workers with signup information, role descriptions, training expectations, and compensation details.
- 🎙️ [Berlin ist eine Mitmachdemokratie: Neue Podcast-Folge zum Stand der Wahlvorbereitung 2026](https://www.berlin.de/wahlen/pressemitteilungen/2026/pressemitteilung.1645191.php) - Status update from 20 February 2026 on the preparations for the September election and the scale of the operational effort.
- 📣 [Weitere Wahlhelferinnen und Wahlhelfer gesucht](https://www.berlin.de/wahlen/pressemitteilungen/2026/pressemitteilung.1660259.php) - April 2026 call for additional election workers, noting roughly 2,500 polling stations, around 1,300 postal-vote stations, and ongoing staffing needs.

------------------------------

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors to this list have waived all copyright and related or neighboring rights to this work.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To add a new entry:
1. Add the resource in the most relevant section.
2. Keep the description short, factual, and useful.
3. Prefer direct links to the primary source, dataset, or official document.
4. Mention important election-year context such as dates, scope, or whether a document applies specifically to 2026.

## About

This list is a compact reference for official Berlin 2026 election data and documentation, with a strong focus on reusable open data, geometry files, deadlines, and voter-facing reference material.

Last updated: 2026-07-26
