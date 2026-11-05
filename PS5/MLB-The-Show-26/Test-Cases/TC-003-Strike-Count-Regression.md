TC-003 — Strike Count Display Regression Test

Game: MLB The Show 26

Platform: PlayStation 5

Test Case ID: TC-003

Feature: Ball-and-Strike Count Display

Test Type: Functional / UI / Regression Testing

Priority: High

Execution Status: Not Run

Tester: Gage Johnson

Test Objective

Verify that the ball-and-strike counter accurately reflects the number of balls and strikes recorded during an at-bat.

This test specifically investigates a previously observed issue in which the on-screen count displayed 0-1 despite two strikes having occurred.

The test will also examine whether the issue persists following game updates.

Preconditions

- MLB The Show 26 is installed and updated.
- The current game version is recorded.
- A playable game mode is available.
- The on-screen ball-and-strike counter is enabled.
- A new at-bat can be started with a 0-0 count.

Test Steps

Step| Test Action| Expected Result
1| Launch MLB The Show 26.| Game launches successfully.
2| Start a baseball game.| Gameplay begins normally.
3| Begin a new at-bat.| Count displays 0-0.
4| Throw or receive a called strike.| Count updates to 0-1.
5| Throw or receive a second strike.| Count updates to 0-2.
6| Throw a ball outside the strike zone that is called a ball.| Count updates to 1-2.
7| Continue the at-bat while observing the counter.| Count remains consistent with umpire calls and game events.
8| Complete the at-bat and begin another.| Count resets to 0-0.
9| Repeat with different batters and pitchers.| Count updates correctly throughout testing.
10| Repeat the test after a future game update.| Previously observed count discrepancies do not recur.

Expected Overall Result

The displayed ball-and-strike count should accurately reflect the actual count throughout every at-bat.

The counter should update immediately after each pitch and reset correctly when a new batter approaches the plate.

Pass Criteria

- All strikes register correctly.
- All balls register correctly.
- Two strikes display as 0-2 when no balls have occurred.
- The counter updates consistently during gameplay.
- New at-bats begin with a 0-0 count.
- No previously observed display discrepancies occur during the tested scenarios.

Fail Criteria

The test fails if:

- The strike count does not update after a valid strike.
- The display shows 0-1 when the actual count is 0-2.
- The ball count displays incorrectly.
- The counter fails to reset between at-bats.
- The displayed count differs from the game's recorded pitch sequence.

Actual Results

Pending test execution.

Reproduction Frequency

Not yet determined.

Regression Testing

The strike-count display issue was previously observed during gameplay.

After a game update, the same scenario should be retested to determine whether the issue remains present.

A successful test does not establish that the defect is permanently resolved. Additional testing may be necessary.

Test Execution Log

Test Date: Pending

Game Version: To be recorded

Game Mode: Pending

Inning: Pending

Batter: Pending

Pitcher: Pending

Expected Count: Pending

Displayed Count: Pending

Screenshot / Video Evidence: Pending

Pass/Fail: Not Tested

Related Bug Report

Bug #004 — Strike Not Counted Correctly

Located in the MLB The Show 26 Bugs folder.

QA Notes

Testing should account for the differences between called strikes, swinging strikes, foul balls, and other pitch outcomes.

Foul balls with two strikes generally do not increase the strike count, except when a foul bunt results in a third strike.

Any discrepancies should be documented with the pitch sequence, game mode, inning, and screenshot or video evidence.

Current Status: Test case prepared; execution pending.
