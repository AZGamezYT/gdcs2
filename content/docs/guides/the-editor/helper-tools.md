---
draft: false
title: Helper Tools
weight: 1110
date: 2026-10-21
description: This guide explains how to use the utility functions the editor provides.
tags:
  - Grade 0
  - Advanced Editor
seo:
  title: How to Use the Visibility, Grid, View and Helper tabs in Geometry Dash.
  description: null
  canonical: ""
  noindex: false
---
{{< callout context="note" title="TLDR - What this guide covers" icon="outline/info-circle" >}}



* RobTop added the Visibility tab, the Grid tab, the View tab, and the Helper tab.
* You can benefit from them in several different ways
* They all have their own unique benefits and uses
* Examples of how you can utilize them effectively



{{< /callout >}}

With the new 2.209 update, RobTop added several tools that you can use in the editor. These include the Visibility tab, the Grid tab, the View tab, and the Helper tab. This guide will explain how to use them, where they are, and what they do.

# 1. Visibility Tab

The visibility tab allows you to hide the Editor's UI and Interface, so you can get a clear look at your own level inside of the editor. Since it removes all menus on your screen, you will be able to see the level the way a normal player would see it when they play the level. It also allows you to take clear screenshots without any visual disruptions, or even to just try to spot any defects you may have in your level.

Below are two images of the regular editor, and the editor with the visibility tab option turned on. If you are on PC, you can also activate it by pressing Tab.

{{< img-grid >}}
{{< img src="https://lh3.googleusercontent.com/d/1tSoGw22tKe8b8NZPC85A9b2NMIU9BSY0" >}}

{{< img src="https://lh3.googleusercontent.com/d/1N-cAUINsrkgvHmN1vBW-B1bFLHN08Ycu" >}}
{{< /img-grid >}}

# 2. Grid Tab

The grid tab allows you to change the size of the grid in the editor. You may be thinking "Well, isn't that kind of useless? compared to the Visibility Tab, the grid tab doesn't really do much!" You'd be right, if not for these factors.

You may have heard of "Grid Snap." anything you move will automatically auto-snap to the center of the nearest grid. Adjusting the grid size with the grid tab can change this, enabling you to make objects lock cleanly to wherever you want. It also changes the distance on how objects move, with a bigger scale with a bigger grid or a smaller scale with a smaller grid.

An example of this could be separating triggers from each other if you'd like to make them more organized and neat. It also allows you to get a clearer reference if you're trying to make objects bigger or smaller.

It is also particularly useful if you have different deco details. Some grid sizes may be better to use as a reference. When creating small details in a block design, you can make the grid size smaller so you can line anything up to make it look as smooth as possible. 

On the other hand, if you're creating a large background, a bigger grid size might be better so you can see everything more clearly and use bigger reference points if you're trying to recreate something, similar to the grid method in portraiture drawing.

You can use Shift+G to toggle on your custom grid size, or use Ctrl+G to swap between them, or just simply click the button with the word "Grid" on it to adjust it.

{{< youtube YCXkqCEfpwY >}}

# 3. View Tab

The view tab is a new feature in the 2.209 update that was put into the main editor tools alongside Build, Edit, and Delete. Prior to this update, players would be forced to go to the pause menu, enable something, and look back. Some of the settings in the View tab weren't even a thing before 2.209. It allows you to turn on many visual settings, like making Shader effects visible or off, Turning the grid on or off, Ignore Damage, LDM, etc.

Most options that were previously in the pause menu are located here now. If you can't find an option, such as Select Filter, it's probably relocated here now.

Here is an image of the new View Tab.

{{< img src="https://lh3.googleusercontent.com/d/1NL3O7U3qQ1JROgPTFxFvYpfJ7iGXoPDK" >}}

The list of options here are:

* **Preview Mode:** Preview the level how you would see it in-game when you are playing it.
* **Hitbox:** Shows hitboxes of objects
* **Hide Invis:** Toggles on or off showing objects with the "Hide" option enabled in Edit Group -> Extra.
* **LDM:** Preview the level how you would see it in-game with Low-Detail Mode.
* **Anims:** Toggles on/off animations of objects in the animated tab.
* **Particle:** Toggles on/off previewing particle objects in the editor.
* **Shader:** Toggles on/off previewing shaders in the editor.
* **Ground:** Shows/Hides the ground.
* **O Info**: Shows/Hides object information when selecting them.
* **Grid:** Toggles on/off the editor grid.
* **Select Filter:** Toggles on/off the select filter option, allowing you to choose certain objects.
* **Ignore Damage:** Ignores deaths during playtesting in the editor.
* **Effect Lines:** Toggles on/off trigger lines that show when it will occur.
* **Dur Lines:** Toggles on/off trigger lines that show the duration of the trigger.
* **Song Lines:** Shows/Hides lines you make yourself in Custom Song Selection -> Create Lines
* **BPM Lines:** Shows/Hides lines made from the BPM trigger.
* **Local Markers:** Shows/Hides where you have died in the level.
* **Global Markers:** Shows/Hides where everyone has died in the level.
* **Marker Labels:** Shows/Hides the amount of times someone has died there.
* **Trace In:** Traces the trigger that activates/affects the selected object.
* **Trace Out:** Traces the objects that the trigger activates/affects; the opposite of Trace In.

Here is a video showcasing these options:

{{< youtube bb-pVktN9Ds >}}

Here is a video showcasing Death Markers:

{{< youtube jUrzbceaC6o >}}

# 4. Helper Tab

The Helper Tab holds buttons that were previously in the Pause Menu prior to the 2.209 update. Options such as Build Helper, Select All, Copy + Color, Reset Unused, Select all Left, are all relocated here. It should also be noted that several creators have not known that you can actually scroll down in this tab, revealing way more options. The buttons all do the same thing, and you should try experimenting them if you haven't already.

{{< img src="https://lh3.googleusercontent.com/d/1giHyQEabmYcDiHhoXN2yDs04ZL1oEqzD" >}}

The list of options here are:

* **Regroup:** Assigns existing triggers the lowest next free group.
* **Build Helper:** Assigns the next free group IDs when copying a trigger setup.
* **Create Loop:** Quickly sets up a spawn loop for your trigger setup.
* **Create Gradient:** Quickly sets up a gradient with vertex mode and assigns group IDs for the corners of the gradient.
* **Align X:** Equally distributes selected objects horizontally.
* **Align Y:** Equally distributes selected objects vertically.
* **Distribute X:** Evenly distributes selected objects on the X axis with the same spacing.
* **Distribute Y:** Evenly distributes selected objects on the Y axis with the same spacing.
* **Select All:** Selects every object in the current layer; can be used with Select Filter option in the Delete tab.
* **Select All Left:** Selects every object in the current layer, but only to the left of the editor; can be used with Select Filter option in the Delete tab.
* **Select All Right:** Selects every object in the current layer, but only to the right of the editor; can be used with Select Filter option in the Delete tab.
* **New Group X:** For multiple groups, new IDs are ordered horizontally, from least to greatest (Left to right).
* **New Group Y:** For multiple groups, new IDs are ordered vertically, from greatest to least (Top to bottom).
* **Copy + Color:** Copies an object while saving it’s color; good for transferring assets over to other levels.
* **Paste + Color:** Pastes an object keeping its color using the next available Color channels.
* **Create Extras:** Adds extra details for certain objects such as filling in the 2.1 rock objects.
* **Unlock Layers:** Unlocks every locked layer at the same time.
* **Reset Unused:** Resets every color channel that is not targeting an object to white. (Unused color channels)
* **Uncheck Portals:** Removes the lines that mark a gamemode portal’s border when you enable the "Preview" option in edit group.

Here is a video showcasing these features:

{{< youtube Jpp53xs6kZ4 >}}
