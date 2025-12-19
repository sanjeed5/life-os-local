# Command: /finish

## Objective
Close out the day and prepare for tomorrow.

## Workflow
1.  **Context**: Read `user.md` to understand the user's priorities and current focus.
2.  **Review**: Read `today.md`. Identify "3 Wins" (completed tasks or positive logs) and celebrate them.
3.  **Log wins**: Add today's wins to `wins.md` under the current month.
4.  **Migrate**:
    -   Identify unfinished tasks in `today.md`.
    -   Move them to the "This Week" section of `inbox.md`.
5.  **Archive**:
    -   Append the entire content of `today.md` to the end of `journal/YYYY/YYYY-MM.md`.
    -   Ensure it is separated by a horizontal rule (`---`).
6.  **Archive complete**: Today's content is now in the journal.
7.  **Update user.md**: If the day revealed new insights, update `user.md`:
    -   Completed a major milestone? → Update "Current Focus"
    -   Discovered a productivity pattern? → Update "Preferences"
    -   Priorities shifted? → Update "Core Priorities"
8.  **Reset today.md**: Replace contents with:
    ```markdown
    # Today

    > Yesterday is archived. Run `/start` to begin a new day.
    ```
9.  **Sync**: Commit and push all changes:
    -   `git add -A`
    -   `git commit -m "📅 YYYY-MM-DD"` (use today's date)
    -   **Safety check**: Verify `origin` remote points to user's private repo (not `upstream`). If not configured, skip push and warn user to run `/setup-private` first.
    -   `git push`
10. **Notify**: "Day finished and synced. What was your favorite moment today?"
