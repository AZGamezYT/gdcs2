---
draft: false
authors:
  - tdp9
title: Level Settings
weight: 1060
date: 2024-04-03T00:00:00.000Z
contributors:
  - tdp9
  - tv_box
description: This guide covers all the settings available at the start of a level.
tags:
  - Grade 0
  - Basic Editor
seo:
  title: How to Edit The Initial Settings of a Level in Geometry Dash
  description: null
  canonical: ""
  noindex: false
---

{{< callout context="note" title="TLDR - What this guide covers" icon="outline/info-circle" >}}
- Level Settings help you customize how your level will start.
- Due to the changing landscape of Update 2.2 compared to Update 2.1, legacy options are placed for compatibility with older levels.

{{< /callout >}}

# 1: Level Settings

How would you like your level to start? The **level settings** can help you set it up. You can access this from the {{< img class="emote" src="images/GDEmotes/Buttons/Settings.png" >}} button in the top right corner of the main editor screen. Clicking on it will bring you to this page.

{{< img src="https://lh3.googleusercontent.com/d/1YBMfoE_jAqBhOEjB5rhqUif89PEWvR3r" >}}

## Color Options

At the top center of the page, you have options to change the color of the Background, Ground, Secondary Ground Color, Ground Line, Middle Ground, Secondary Middle Ground Color, and all color channels (in the more section). The plus symbols next to the labels will bring you back to the main editor screen and allow you to choose a color using a HSV slider.

## BG, G, and MG selectors

To the right of the screen, there are three selectors where you can choose the starting background, ground, and the middle ground of the level. If the MG selector has a cross on it, the middle ground is removed.

## Font

The font button will allow you to scroll through and select a font used in the level’s text objects. There are currently 60 fonts to choose from.

## Speed

Here you can select the starting speed of the level. There are five different speeds to choose from.

## Mode

Here you can select the starting gamemode of the level. There are eight gamemodes to choose from.

## Game Type

Game Type allows you to choose between classic mode and platformer mode for your level. Note that the wave and swing game modes are disabled for platformer mode.

## Select Song

Select the starting song for the level from the list of default songs or [use a custom song](/docs/guides/the-editor/choosing-a-song).

## Options

Gives extra options for the level, which includes the following:
- **Mini Mode**: Shrinks the player’s size from the start of the level.
- **Dual Mode**: Puts the player into dual mode at the start of the level.
- **2-Player Mode**: Sets the level into 2-player mode, where dual icons are controlled by two different control sets.
- **Mirror Mode**: Sets the screen to be mirrored at the start of the level.
- **Flip Gravity**: Makes the player's gravity upside down at the start of the level.
- **Rotate Gameplay**: Rotates the gameplay at the start of the level.
- **Reverse Gameplay**: Makes the player go backwards from the start of the level instead of forwards.
- **No Time Penalty**: An option that only affects platformer mode. As you play a level in platformer mode, you lose 1,000 points per second. This option removes this point loss.
- **Spawn Group**: Spawns the player at the position of an object with the selected group. If multiple objects have the same group, one will be chosen at random. In normal mode, only the object’s y-value is relevant for spawning.

{{< youtube pGwNAlpqrOc >}}

# 2. Legacy Options

Within the options menu is another {{< img class="emote" src="images/GDEmotes/Buttons/Settings.png" >}} icon which leads to the legacy options menu. These options make it so that levels before recent updates can work like they did before the update. For 2.2 levels, it’s recommended to leave these options alone.
- **Allow Multi-Rotation**: Objects that are being rotated by 2 or more different rotate triggers will rotate properly.

{{< youtube WXTGlvQTBRg >}}

- **Enable 2.2 Changes**: Changes progression in the level from being based on player position to being based on the verification completion time.
- **Allow Static-Rotate**: Makes it so that static objects can visually rotate properly. Hitboxes are not rotated. This only works in the editor.

{{< youtube O28Ru0-MghQ >}}

- **Enable Player Squeeze**: Fixes a bug that allows a player to “squeeze” into an object when it shouldn’t.

{{< youtube njNbKLisV5w >}}

- **Fix Gravity Bug**: Fixes a bug where upside down gravity had different physics than normal gravity.
- **Fix Negative Scale**: Fixes a bug where scaling an object into the negatives using scale hacks would remove or massively shrink a hitbox for an object.
- **Fix Robot Jump**: Fixes moments where jumping at the right time on a slope or before a pad as a robot would give a massive jump height boost.

{{< youtube Y9qBZxjDCK8 >}}

- **Dynamic Level Height**: Increases the level height as you build higher. This is similar to how a level’s length increases as you build further.
- **Sort Groups**: Makes it so that spawned groups are spawned from left to right.
- **Fix Radius Collision**: Fixes a bug where circular hitboxes wouldn’t properly register by adding a circle hitbox to the player for those interactions.

{{< img src="https://lh3.googleusercontent.com/d/1xsVBXjHq9fAaUk_h8AHatNtDXbg6f76I" >}}

- **Reverse Sync**: Speeds up or slows down the player so that the music can stay in sync whenever a direction change occurs.
- **Decrease Boost Slide**: Lessens how much the player slides after being launched by a dash orb or moving objects.

{{< youtube uT4GVrRlYfk >}}