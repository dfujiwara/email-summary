# Email Summary

A Claude skill that categorizes and summarizes unread Gmail threads into a Claude Doc, with action items at the top.

## Setup

1. Copy `categories.example.yaml` to `categories.yaml`.
2. Customize the categories, sender rules, and allowed link domains.
3. Run the `/email-summary` skill with the required Gmail and Claude Docs tools available.

`categories.yaml` is ignored by Git because it may contain personal information and a private document link. On its first run, the skill creates a digest document and stores its link in that file.
