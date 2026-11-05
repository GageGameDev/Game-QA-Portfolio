Bug #002 — Player Join Requests Not Displayed After App Resumes

Game: Pokerrr 2

Platform: Android

Category: Application Lifecycle / UI Synchronization

Severity: High (Provisional)

Status: Open — Workaround Confirmed

Bug Description

Following a recent application update, Pokerrr 2 temporarily freezes when returning to the application after switching to another app.

Although the game eventually becomes responsive, incoming player requests to join a hosted poker game no longer appear.

Requests display normally when the host stays within the application. After switching away and returning, requests remain invisible until the application is completely restarted.

Steps to Reproduce

1. Launch Pokerrr 2.
2. Host an active poker game.
3. Remain in the application and verify that incoming join requests appear normally.
4. Switch to another application.
5. Return to Pokerrr 2.
6. Wait for the temporary freeze to resolve.
7. Have another player request to join the game.
8. Observe that the request does not appear.
9. Completely close and restart Pokerrr 2.
10. Observe that the missing request becomes visible.

Expected Result

The application should resume normally and continue displaying incoming player requests without requiring a restart.

Actual Result

The application temporarily freezes after resuming. Although normal responsiveness returns, incoming player requests remain invisible until the application is restarted.

Reproduction Rate

- Temporary freezing: Reported every time the application is backgrounded and reopened.
- Missing player requests: Observed after returning from another application.
- Control condition: Requests display normally when the application remains active.

Confirmed Workaround

Completely close and restart Pokerrr 2 to restore visibility of incoming requests.

QA Notes

The issue began following a recent update.

The behavior suggests a possible application lifecycle or synchronization problem involving incoming requests after resuming from the background.

The underlying cause has not been confirmed.

Impact: Hosts may unknowingly leave players waiting for approval, disrupting game administration.
