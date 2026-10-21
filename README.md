# Compendium data

The published list for the Compendium Chrome extension, served at `https://data.corpusmedix.com.au/`.

| File | What it is |
|---|---|
| `v1/compendium.json` | The live list. Installed extensions download it about once a day. |
| `v1/compendium-preview.json` | The preview list, read by preview builds of the extension before an update goes live. |

**These files are generated. Don't edit them by hand.** They're built from the Master List, a Google Sheet, after every row has been checked. Each commit here is a published version, so the history shows what the extension received and when, and reverting a commit restores an earlier version.

`v1` is the file layout's schema version. If the layout ever changes in a way older extensions can't read, the new layout is published under `v2/` alongside it, and `v1/` keeps working.
