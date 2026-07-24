# Org Chart Tool

A self-contained browser tool for building and visualizing org charts from Workday exports. No installation, no backend, no account required — open the link and go.

**[Launch the tool →](https://covermymeds.github.io/claude-orgchart/claude-orgchart.html)**

---

## What it does

- **Import from Workday** — Upload a "My Team Employment Data" XLSX export and the tool builds the org chart automatically
- **Edit freely** — Add, remove, or rearrange people; change titles, levels, and reporting relationships
- **Save your work** — Charts save to your browser automatically, or export as JSON to save locally
- **Export to PNG** — For use in decks or documents
- **Multiple layout modes** — Adjust spacing, zoom, and orientation to fit your needs

## Your data stays with you

Org charts are saved in your browser only. Nothing is uploaded to any server. If you're working on a draft or sensitive reorg, your work is not visible to anyone else unless you explicitly share the JSON export.

## How to build an org chart

### From a Workday export (recommended)
1. In Workday, run the **My Team Employment Data** report for your org
2. Export as XLSX
3. Open the tool and click **Upload Workday XLSX**
4. The chart builds automatically from the manager hierarchy in the report

### From scratch
Click **Add person** to start building manually. Set each person's manager to define the hierarchy.

## Saving and sharing

| Method | What it does |
|---|---|
| **Browser save** | Saves automatically to your browser. Persists across sessions on the same machine. |
| **Export JSON** | Downloads a `.json` file you can store locally or share with someone else |
| **Import JSON** | Load a previously exported chart from a JSON file |
| **Export PNG** | Downloads a image of the current chart view |

> **Note:** Browser saves are tied to your browser on your machine. To move a chart to another computer, use Export JSON.

## Tips

- **Reorg planning** — Export your current chart as JSON first, then make changes. You can always reimport the original to start over.
- **Multiple orgs** — Each browser save slot holds one chart. Use JSON exports to maintain multiple versions.
- **Large orgs** — The tool handles orgs of 100+ people. Use zoom and spacing controls to navigate.

---

## Contributing / updating the tool

The entire tool is a single HTML file (`claude-orgchart.html`). To update:
1. Replace the file in this repo with the new version
2. GitHub Pages will reflect the change within a minute or two

No build step, no dependencies, no deployment pipeline.

---

*Built for internal CoverMyMeds use. Questions or issues — reach out to Greg Hart.*
