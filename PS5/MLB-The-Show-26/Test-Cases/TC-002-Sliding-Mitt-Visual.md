TC-002 — Sliding Mitt Equipment and Animation Verification

Game: MLB The Show 26

Platform: PlayStation 5

Test Case ID: TC-002

Feature: Player Equipment / Sliding Animations

Test Type: Visual / Functional / Regression Testing

Priority: Medium

Execution Status: Not Run

Tester: Gage Johnson

Test Objective

Verify that a player's equipped sliding mitt appears on the correct hand during gameplay, baserunning animations, sliding sequences, and instant replays.

This test investigates potential inconsistencies between equipment customization settings and the equipment displayed on the player's character model.

Preconditions

- MLB The Show 26 is installed and updated.
- A player with an available sliding mitt is selected.
- The sliding mitt is equipped on a specific hand.
- The selected equipment configuration is documented.
- A game mode supporting baserunning and sliding is available.

Test Steps

Step| Test Action| Expected Result
1| Launch MLB The Show 26.| Game launches successfully.
2| Open the player's equipment customization settings.| Equipment options display correctly.
3| Equip the sliding mitt on the left hand, if supported.| The mitt appears on the selected hand.
4| Save the equipment settings.| Changes are saved successfully.
5| Enter a game with the customized player.| Player model loads with the correct equipment.
6| Observe the player while standing on base.| Sliding mitt appears on the configured hand.
7| Perform a slide into a base.| Sliding animation maintains the correct mitt placement.
8| Review the slide using instant replay.| Equipment appears consistently in replay.
9| Repeat the test with the opposite hand, if supported.| Mitt placement follows the selected configuration.
10| Restart the game and reload the player.| Saved equipment settings remain consistent.

Expected Overall Result

The sliding mitt should consistently appear on the player's configured hand during customization, gameplay, sliding animations, and replays.

Pass Criteria

- Sliding mitt matches the selected equipment configuration.
- Equipment placement remains consistent across animations.
- Instant replays display the correct equipment.
- Saved equipment settings persist after restarting.

Fail Criteria

The test fails if:

- The sliding mitt appears on the wrong hand.
- Equipment changes position unexpectedly during animations.
- The replay displays different equipment placement from gameplay.
- Saved equipment settings are not retained.

Actual Results

Pending test execution.

Reproduction Frequency

Not yet determined.

Test Execution Log

Test Date: Pending

Game Version: To be recorded

Player / Game Mode: Pending

Configured Mitt Hand: Pending

Observed Mitt Hand: Pending

Screenshot or Video Evidence: Pending

Pass/Fail: Not Tested

Related Bug Report

Bug #003 — Sliding Mitt Appears on Wrong Hand

Located in the MLB The Show 26 Bugs folder.

QA Notes

The issue was previously observed during gameplay. This test case provides a structured procedure for investigating equipment placement inconsistencies.

Testing should include different sliding animations, camera angles, and player models when possible.

Any discrepancies should be documented with screenshots or video evidence.

Current Status: Test case prepared; execution pending.
