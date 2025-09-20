# Poetry — Atherapath

![Build Status](https://github.com/Atherapath/poetry/actions/workflows/generate.yml/badge.svg)
![License](https://img.shields.io/github/license/Atherapath/poetry)
![Latest Edition](https://img.shields.io/badge/edition-1-blue)

An archive of generated poetry and images.  
Part of the [Atherapath](https://github.com/Atherapath/atherapath) project.

---

## Extended Description (optional)

This repository gathers poems generated within the Atherapath framework.  
Each poem is paired with an image, and together they form an evolving archive.  

- **`/poems`** → individual works in markdown  
- **`/images`** → generated illustrations, one per poem  
- **`/editions`** → curated collections (books, volumes, or themed sets)  
- **`.github/workflows`** → automation workflows that keep the archive alive  

The aim is to create a *living poetry book* that can be browsed one piece at a time or compiled into formal editions.

---

## Repository Structure

```text
poetry/
├── README.md              # Overview of the repo
├── poems/                 # Individual works stored as markdown
│   ├── 001-first-poem.md
│   ├── 002-another-title.md
│   └── ...
├── images/                # Generated illustrations (linked from poems)
│   ├── 001-first-poem.jpg
│   ├── 002-another-title.jpg
│   └── ...
├── editions/              # Collected “book” releases
│   ├── edition-1.md
│   └── edition-2.md
├── .github/
│   └── workflows/
│       └── generate.yml   # GitHub Action: auto-generate poems + images
└── LICENSE
