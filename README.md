# ged-view.com (description only repo - no code)

**A modern, privacy-first GEDCOM viewer. Everything runs in your browser.**

[**ged-view.com**](https://ged-view.com) &nbsp;·&nbsp; No account &nbsp;·&nbsp; No uploads &nbsp;·&nbsp; No data leaves your device

![Home](Images/home.png)

---

## What is this?

Most genealogy platforms are racing toward DNA analysis and AI-assisted research. That's useful, but it leaves a gap: there's no clean, modern way to just *explore* your family data. The richly detailed GEDCOM file you already have on your hard drive deserves better.

I built ged-view as a personal tool to share my own GEDCOM with family in a way they'd actually want to use. Since I'm a developer, a few months later it had grown into a full-featured viewer that works with any GEDCOM file from any platform. The version at [ged-view.com](https://ged-view.com) is a public fork of that private family tool.

Import your `.ged` file and everything happens inside your browser: parsing, layout, geocoding, diagrams. Nothing is uploaded. Nothing is sent anywhere. No account required.

---

## Features

### Overview & Stats
See a breakdown of people, families, last names, locations, and timespans at a glance.

![Overview](Images/overview.png)

### Family Tree
Visualize your ancestors and descendants in an interactive graphical tree.

![Family Tree](Images/tree.png)

### Charts
Generate descendant charts and relation report diagrams for any individual in your tree.

![Descendant Chart](Images/descendant%20chart.png)
![Relation Report Chart](Images/relation%20report%20chart.png)

### Data Table
Browse every individual with sortable, filterable columns for quick searching.

![Data Table](Images/data.png)

### Profile
View a detailed page for each individual: life events, family connections, photos, and sources.

![Profile](Images/profile.png)

### Timeline
Explore every birth, death, marriage, and event across all generations in chronological order.

![Timeline](Images/timeline.png)

### Gallery
View photos and media embedded in your GEDCOM file in one place.

![Gallery](Images/gallery.png)

### Calendar
Browse birthdays and anniversaries laid out in a calendar view.

![Calendar](Images/calendar.png)

### Map
Visualize birth, death, marriage, and burial locations pinned on an interactive world map.

![Map](Images/map.png)
![Migration Paths](Images/migration.png)

### Archive
Browse sources, citations, and repository records linked to individuals in your tree.

![Archive](Images/archive.png)

### History
See which people and families were most recently changed, based on the modification dates recorded in your GEDCOM file.

![History](Images/history.png)

### Issues
Scan your GEDCOM for data problems: impossible dates, missing fields, and inconsistencies, all in one report.

![Issues](Images/issues.png)

### Editor
View and edit the raw GEDCOM file directly, with each level indented for readability. (in beta stage)

### Exports
Export the tree and charts to PDF or PNG, the overview, profiles, timeline, and calendar year to PDF, and the data table to CSV or Excel. Every export is kept on your browser for 7 days.

![Exports](Images/exports.png)

### Blog
Guides, tips, and articles on genealogy research, GEDCOM files, and getting the most from your family data.

---

## Supported platforms

Export a GEDCOM from any of these and import it at ged-view.com:

- **Ancestry:** Tree Settings → Export Tree → Download GEDCOM
- **MyHeritage:** Manage tree → Export → Export to GEDCOM
- **FamilySearch:** Tools → Export Family Tree → GEDCOM
- **RootsMagic:** File → Export → Export to GEDCOM
- **Gramps:** Family Trees → Export → GEDCOM
- **Family Tree Maker:** File → Export → GEDCOM
- **WikiTree:** Profile → Actions → Export → GEDCOM

Not sure where your file is? Any software that handles family trees can almost certainly export a `.ged` file.

There are also sample files on the site if you want to explore before importing your own.

---

## Privacy

Your data never leaves your device.

When you import a GEDCOM file, it is read and processed entirely inside your browser. The parsing, relationship calculations, geocoding, and diagram rendering all happen locally. Nothing is uploaded to any server. No data is sent to any third party.

Files you import are saved in your browser's local storage so they're available next time you visit. This data stays on your device and can be cleared at any time.

---

## Roadmap

**Completed recently**
- Descendant chart
- Relationship finder (e.g. "7th cousin twice removed")
- Localization / interface translations
- Issues / data quality report
- History view of recently changed people and families
- Raw GEDCOM editor
- Exports to PDF, PNG, CSV, and Excel across every view
- Larger file support (now handles up to ~80 MB / 6,000 people in the tree view; 50,000+ across all other views)
- Calendar sync (Google Calendar, Apple Calendar, etc.)

**Planned**
- Theme builder for colors, fonts, and card styles
- Document & media attachments directly to individuals and events

**Long-term**
- Optional accounts and cloud sync (still fully private, data never sold or shared)
- Family sharing with access controls
- Collaborative editing with version history

---

## Feedback

I'm looking for input from people who actually use genealogy software:

1. Which views would you use regularly?
2. What's missing that would make this useful in your real research workflow?
3. Does the privacy angle (nothing leaving your browser) matter to you?

Open an issue here or use the feedback form on the site.

---

## License

This is not open source software. The source code, design, and algorithms are proprietary and may not be copied, reproduced, or reused without explicit written permission. Some third-party libraries used are open source under their respective licenses. See [Terms of Use](https://ged-view.com/terms) for full details.

© 2026 Aleksej Cupic. All rights reserved.
