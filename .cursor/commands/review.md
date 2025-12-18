# Command: /review

## Objective
Weekly reflection to celebrate wins, identify patterns, and set intentions.

## Workflow
1.  **Context**: Read `user.md` to understand current priorities and preferences.
2.  **Gather**: Read the last 7 days from `journal/YYYY/YYYY-MM.md`.
3.  **Wins**: Identify and list the top 5 completed tasks or positive moments.
4.  **Patterns**: Note any recurring themes (e.g., "You crushed mornings but stalled after 3pm").
5.  **Stuck**: Identify tasks that appeared multiple days but never got done. Ask: "Should we break this down, delegate, or drop it?"
6.  **Backlog Audit**: Skim `backlog.md`. Ask if any items should be promoted to next week's focus or archived to "Someday".
7.  **Intention**: Ask the user: "What's the ONE thing you want to accomplish next week?"
8.  **Update user.md**: Based on the week's patterns and new intention:
    -   Update "Current Focus" with the new intention
    -   Update "Preferences" if work style patterns emerged
    -   Update "Core Priorities" if they've shifted
9.  **Sync**: Commit and push all changes:
    -   `git add -A`
    -   `git commit -m "📊 Week review - Mon DD to Mon DD"` (use the week's date range)
    -   `git push`
10. **Notify**: Summarize with "Weekly review complete and synced. Your focus for next week: {Intention}."
