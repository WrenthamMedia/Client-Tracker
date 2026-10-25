# Client Tracker

Wrentham Media's sales pipeline for local business websites.

Businesses move through seven stages:

Found → Contacted → Meeting set → Building concept → Pitched → Live → On retainer

## Features

- **Pipeline board.** Drag cards between stages, or tap "Next stage →" on a phone.
- **Follow up today.** Lists every business whose follow-up date is today or overdue.
- **Money strip.** Shows monthly recurring income, clients on retainer, deals in play, and follow-ups due.
- **Client details.** Each card holds contact info, package, retainer amount, concept and live site links, and notes.

## How it runs

Everything is in one file, `index.html`.

Saving uses the claude.ai artifact database (`window.claude.use("db")`, collection `clients`). The live version with saved data runs as a Claude artifact.

If you open `index.html` anywhere else, the tracker still works, but changes are kept only until you close the page. A banner at the top says so.
