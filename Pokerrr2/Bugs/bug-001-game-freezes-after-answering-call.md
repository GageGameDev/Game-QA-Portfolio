# Bug #001 - Game Freezes After Answering Incoming Phone Call

## Game
Pokerrr2

## Platform
Mobile Phone

## Category
App Stability / Interruption Handling

## Severity
Medium

## Priority
Medium

## Description
If an incoming phone call is answered while Pokerrr2 is running, the game can freeze after returning to the app.

The player is unable to continue using the game normally and must fully close and restart the app.

## Steps to Reproduce
1. Launch Pokerrr2.
2. Enter a game or remain active inside the app.
3. Receive an incoming phone call.
4. Answer the call.
5. End the call.
6. Return to Pokerrr2.
7. Attempt to continue using the app.

## Expected Result
Pokerrr2 should resume normally after the phone call ends.

The player should be able to continue using the app without restarting it.

## Actual Result
The game freezes after returning from the phone call.

The player must close Pokerrr2 and restart the app before continuing.

## Reproduction Rate
Observed multiple times.

Exact reproduction rate needs additional testing.

## Notes
The issue appears related to interruption handling when the app is sent to the background during an active phone call.

Additional testing should check:
- Whether the issue occurs during active games only or also in menus
- Whether declining a call causes the same problem
- Whether the issue occurs with other interruptions such as notifications or switching apps
- Whether the issue happens consistently on the same phone model and operating system version

## Evidence
A screen recording showing the app before the phone call and the frozen state after returning would be useful.