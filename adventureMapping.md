# Adventure Mapping for STM-IF

## Overview

This guide explains how to create YAML files for interactive storytelling with U-Stags, using `adventureMap-Example.yaml` as a reference.

## YAML Structure for STM-IF

- **Title**: The game's title.
- **Start**: The starting point of the story.
- **Variables**: Define variables to track the game state (e.g., `trustLevel`).
- **Steps**: The main content of your game, each step represents a scenario or choice point.
  - **Description**: Details of the current scenario.
  - **Options**: Choices available to the player, leading to different steps.
- **Endings**: Possible conclusions of the game, triggered by the players' choices.

## Building Your Adventure

1. **Define the Narrative**: Outline your story, including key events and decision points.
2. **Implement in YAML**: Translate your narrative into the YAML structure. Use variables to influence game flow and outcomes.
3. **Test and Iterate**: Playtest and refine your YAML file for a smooth, engaging game experience.

Refer to `adventureMap-Example.yaml` in the `InteractiveExamples` folder for a practical example of a game narrative implemented using this format.
