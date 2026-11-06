---
on: workflow_dispatch

permissions:
  contents: read
  pull-requests: read

engine: copilot
network: defaults

safe-outputs:
  create-pull-request:
    title-prefix: "[Mona Website Update] "
    draft: true
    max: 1

---

# GitHub Info Website Updater

## Purpose
Keep Mona's GitHub Info website updated with relevant GitHub announcements.

## Instructions

1. Read Mona's notes from the repository. Locate the relevant notes file before making changes.

2. Review recent announcements from:
   - https://github.blog/
   - https://github.blog/changelog/

3. Identify recent updates relevant to Mona's GitHub Info website.

4. Compare the announcements with the existing website content.

5. Draft appropriate website changes based on relevant announcements.

## Files to modify
- Only modify existing website content files.
- Do not modify package configuration, application dependencies, or unrelated files.
- Do not modify Mona's original notes.

## Sources and updates
- Include links to the original GitHub Blog articles.
- Include links to the GitHub Changelog entries.
- Explain why each update is relevant to the website.

## Pull Request
- Create a draft pull request containing the proposed website changes.
- Include a clear title and description.
- Summarize the files changed.
- Include the sources consulted and updates used.
- Highlight any assumptions or changes requiring human review.

## Review requirements
- Verify all source links.
- Ensure website content remains consistent with the existing style.
- Do not invent announcements or technical details.
- Do not merge the pull request automatically.
- Require human review before merging.
-