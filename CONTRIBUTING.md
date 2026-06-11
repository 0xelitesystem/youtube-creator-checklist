# Contributing a Checklist Item

## Bar for adding an item

A new item belongs in a checklist if:

- It's a mistake creators actually make repeatedly (you've seen it more than once)
- It's quickly verifiable (under 30 seconds)
- It's not platform-specific in a way that'll be obsolete in 6 months
- It's not subjective ("make sure your video is good" is not a checklist item)

## Submission

1. Identify which checklist the item belongs in (don't add it to ALL of them)
2. Place it in the most fitting section
3. Open a PR explaining the mistake the item prevents

PR title: `add item: [checklist] - [short description]`

Example: `add item: pre-publish - check thumbnail safe area`

## What gets rejected

- Items duplicated across checklists (pick the one place it belongs)
- Items that are really 3 items disguised as one
- Items based on platform features that change frequently
- Items that recommend specific paid tools
- Items that encourage manipulative tactics ("comment 5 times to boost engagement")

## Updating an item

If a YouTube feature changes (or a checklist item becomes outdated):

PR title: `update item: [checklist] - [item]`

Explain what changed and why.

## Removing an item

If an item no longer applies (feature removed, never mattered, replaced by better item):

PR title: `remove item: [checklist] - [item]`

Open an issue first if it's a contentious removal.

## New checklist proposal

If you want to add a whole new checklist (e.g. "live stream pre-stream checklist"):

1. Open an issue first describing the use case
2. Wait for maintainer / community feedback
3. PR the new checklist with at least 15 items

Don't PR a 5-item checklist; merge those into existing ones instead.
