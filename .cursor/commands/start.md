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
    -   Read `backlog.md`.
    -   Identify 1 high-priority "Focus" task and 2-3 standard "Tasks".
    -   Prioritize tasks that align with `user.md` "Core Priorities".
    -   Move them from `backlog.md` to `today.md`.
    -   **Time Blindness**: Add a duration estimate and suggested time block to each task, respecting the user's preferred work style from `user.md`.
6.  **Notify**: "Day started. Your focus is: {Focus Task}."
