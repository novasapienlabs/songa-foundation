# Change requests

Anyone on the Songa team can ask for a change to this set. Joshua gathers the requests, and Krister approves them. [Joshua, Nov 23, 2026]

## How a change happens

Changes flow one way: from this repository, the source, to the PDFs in Drive. Nobody edits the Drive copies directly. [Joshua, Nov 23, 2026]

1. **Request:** send Joshua what you'd change, where (file and section), and why. Say where it comes from: something Krister said, a document, a decision, or your own suggestion.
2. **Approve:** Joshua brings it to Krister, who approves, adjusts or declines it.
3. **Update the source:** Joshua makes the approved change in this repository.
4. **Log it:** Joshua adds a dated line to `CHANGELOG.md`: what changed, who asked, that Krister approved, and which Drive files were rebuilt.
5. **Rebuild:** Joshua rebuilds the affected PDFs and replaces them in Drive.

## Safety net

A weekly check compares the edit dates of the Drive files with `CHANGELOG.md` and flags any edit that isn't logged. Flags go to Joshua first, and only real conflicts go to Krister. It isn't running yet.

## A good request

- Names the file and section.
- Gives the new wording, or the gap to fill.
- Says where it came from, so the section's status and source can be set right.
- Leaves a blank as a blank when nobody knows yet. An honest gap is better than a guess.

## Open

- Who gets access to this repository and to the Drive folder.
- Whether team members send requests by email, message, or a GitHub issue.
