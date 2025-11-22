# Notes Folder Upkeep & Collaboration Guidelines

## Branching
- Make all significant updates on dedicated branches using clear, descriptive names:
  - E.g., `notes/update-budget-jan2026`, `notes/add-market-analysis`, `app-features/user-management`
- Never push directly to `main` or production branches.

## Pull Requests (PRs)
- All changes must be merged through pull requests.
- Pull requests allow other AIs or team members to review, discuss, and approve/document changes.
- Clearly reference what is being changed/added in the PR description.

## Commit Messages
- Use descriptive, concise commit messages.
  - Good: `Add section on marketing KPIs`
  - Bad: `update`
- The message should summarize the change so someone scanning the history can see what’s new or different.

## Issue Tracking
- Use GitHub issues to propose, assign, and discuss tasks or content changes.
- Reference issue numbers/titles in commit messages and PRs when relevant.
- Use issues for requests, enhancements, or bug reports related to both code and documentation.

## Naming Conventions for Notes Files
- Use consistent, descriptive filenames—for example:
  - `notes/filament-suppliers.md`
  - `notes/sales-analysis-Q1.md`
  - `notes/business-plan-revised-2026.md`
- Use hyphens to separate words; add a date or version when appropriate for historical tracking.

## Ongoing Maintenance
- Periodically review the notes folder to:
  - Archive or delete outdated material.
  - Link new insights from the main plan for context/discoverability.
- If multiple AIs (or team members) are contributing, everyone must observe the same branch-and-PR procedure to avoid conflicting edits.
- When updating content on request, always follow this process:
  1. Draft Markdown for proposed changes.
  2. Copy updates to the appropriate file in the repo.
  3. Commit to a dedicated branch and open a pull request for review and merging.

## Coordination Among Multiple AIs or Contributors
- Always communicate status of in-progress updates (via issues or comments).
- Respond to review feedback promptly and adjust as needed.
- Coordinate archival or renaming of legacy files to ensure discoverability and correctness.

---

**Reminder:** This process ensures your GitHub repository remains both a codebase and a living documentation hub for your business, with clear collaboration standards for all contributors—human or AI.