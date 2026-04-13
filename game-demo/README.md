# Game Demo Test Portfolio

## Project Overview
This portfolio presents the testing work for a UE4 first-person timed shooting demo.  
The demo includes start / pause / restart flow, score logic, target spawning, HUD feedback, and result screen interaction, with a focus on gameplay rule validation, state transitions, UI feedback, and regression verification.

## Tech Stack
`UE4.27 + Blueprint + Windows`

## Core Gameplay Focus
This demo is suitable for demonstrating game QA thinking because the main risks are not only “whether the game can run”, but also whether the gameplay loop is stable and testable. The key risks include:

- game state transitions between start, in-progress, pause, result, and restart
- score addition / deduction correctness
- target spawn and refill stability
- projectile hit logic and duplicate settlement risks
- HUD, pause menu, and result screen interaction
- alignment between crosshair and projectile direction
- regression verification for representative gameplay defects

## Portfolio Contents
This folder currently includes:

- `项目说明.md`
- `测试用例清单.md`
- `核心测试用例展开.md`
- `缺陷清单.md`
- `代表性缺陷详情.md`
- `测试总结.md`

## Testing Highlights
The materials in this folder mainly demonstrate:

- gameplay rule analysis and risk identification
- test case design for core flow, abnormal flow, and state transitions
- bug tracking and regression verification for representative gameplay issues
- UI feedback and interaction validation
- structured game test documentation output

## Notes
This repository contains desensitized test artifacts for portfolio presentation only.  
Executable files, source assets, and large video files are not included in the initial upload.
