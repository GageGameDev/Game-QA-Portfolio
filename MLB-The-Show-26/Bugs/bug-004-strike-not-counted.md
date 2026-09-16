# Bug #004 - Strike Occasionally Not Counted During At-Bat

## Game
MLB The Show 26

## Platform
PlayStation 5

## Mode
Ranked Co-op

## Category
Gameplay / Rules Logic

## Severity
High

## Priority
High

## Description
A pitch can be called a strike by the umpire and acknowledged as a strike by the commentary, but the on-screen count does not increase.

For example, when the count is 0-1 and another strike occurs, the count may remain 0-1 instead of updating to 0-2.

## Steps to Reproduce
1. Launch MLB The Show 26.
2. Enter a Ranked Co-op game.
3. Begin an at-bat.
4. Reach a 0-1 count.
5. Throw or receive another pitch that is called a strike.
6. Listen to the umpire and commentary confirm the strike.
7. Observe the on-screen ball-strike count.

## Expected Result
The count should update from 0-1 to 0-2 after the second strike is called.

## Actual Result
The umpire and commentary recognize the pitch as a strike, but the displayed count remains 0-1.

The batter effectively receives an additional pitch because the strike is not correctly added to the count.

## Reproduction Rate
Observed approximately once per game during the original testing period.

## Notes
This issue is more serious than a visual display error because it appears to affect the actual at-bat state and can give the batter an additional pitch.

Possible areas to investigate include online synchronization, pitch result processing, and count-state tracking.

## Evidence
Video is preferred because it can capture the pitch result, umpire call, commentary, and count display at the same time.
