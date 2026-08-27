# Take-Home Assessment

Two independent tasks. Fork this repository, work on your fork, and read the PDF in
each task folder before writing a single line of code.

## Repository layout

```
task1/   TASK1.pdf  <- read this first
         dataset/   <- the CSVs for Task 1 (UTF-8 BOM, plus _manifest.json)

task2/   TASK2.pdf  <- read this first
         dataset/   <- the CSVs for Task 2 (UTF-8 BOM, plus _manifest.json)
```

## Task 1 -- in one paragraph
Three systems recorded the same pharmacy orders, none of them agreeing. Unify them:
map every supplier-side account name to the real pharmacy in the registry, recover the
missing pharmacy locations from dirty delivery addresses, build one canonical revenue
ledger, and answer four ranking questions (areas, pharmacies, suppliers). Deliver the
results plus a small local website to browse and filter them.
**Everything is specified in `task1/TASK1.pdf`.**

## Task 2 -- in one paragraph
A field rep must visit 16 pharmacies tomorrow, in one area. From the historical visit
log and the invoices, figure out how long stops take, when each pharmacy is best
visited, and how long drives really feel -- then produce the itinerary, prove it fits
the day, and ship a small page that draws the route. **Specified in `task2/TASK2.pdf`.**

## Ground rules (short version; the PDFs are the contract)
- Offline code only -- no network calls, no model APIs inside your submission.
- One command reruns everything, deterministically.
- AI assistants allowed and expected; keep an honest `AI_DISCLOSURE.md`.
- The two datasets are intentionally similar; each task is standalone and graded alone.

## Deliverables
- Task 1: `TASK1_<name>.zip` -- code + outputs + website + `AI_DISCLOSURE.md`.
- Task 2: `TASK2_<name>.zip` -- code + outputs + route viewer + `AI_DISCLOSURE.md`.
- Work on your fork of this repository; the deliverable is your fork link.

## Questions
Ammar Yasser -- +201275475215 (anything about this assessment).
