# Command: /onboard (or /init)

## Objective
Interview the user to populate `user.md` and personalize the LifeOS experience.

## Workflow
1.  **Welcome**: Greet the user and explain that you will configure their profile.
2.  **Interview**: Ask the user the following questions one by one (or in small groups):
    -   **Identity**: "What is your Name, Role, and current Timezone?"
    -   **Priorities**: "What are your top 2-3 main priorities or active projects (North Stars) right now?"
    -   **Style**: "How do you prefer to communicate? (e.g., Concise, Detailed, Socratic) and what is your preferred work style?"
3.  **Update**:
    -   Replace the placeholders in `user.md` with the user's answers.
    -   Ensure the formatting matches the existing Markdown structure.
4.  **Verify**:
    -   Display the updated content of `user.md`.
    -   Ask the user for confirmation.
5.  **Next Step**:
    -   Once confirmed, suggest running `/start` to begin their first official day.
