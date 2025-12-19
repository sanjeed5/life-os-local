# Command: /start

## Objective
Initialize `today.md` for a fresh start.

## Workflow
1.  **Context**: Read `user.md` to understand priorities, work style, and current focus.
2.  **Archive**: If `today.md` contains data from a previous date, append it to the end of `journal/YYYY/YYYY-MM.md` (create file if needed).
3.  **Reset**: Clear `today.md`.
4.  **Template**: Write the header:
    ```markdown
    # Today: YYYY-MM-DD
    
    ## 🎯 Focus (The One Thing)
    - [ ] 

    ## 📋 Tasks
    - [ ] 

    ## 🧠 Log & Notes
    ```
5.  **Fill**:
    -   Read `inbox.md`.
    -   **Priority order**: "This Week" → "Projects" → "Unsorted". Ignore "Someday".
    -   Identify 1 "Focus" task (most aligned with `user.md` Core Priorities) and 2-3 "Tasks".
    -   Move them from `inbox.md` to `today.md`.
    -   **Habits**: Check the "Habits" section—add any daily recurring items to today's tasks.
    -   **Time Blindness**: Add a duration estimate to each task, respecting the user's work style from `user.md`.
6.  **Notify**: "Day started. Your focus is: {Focus Task}."
