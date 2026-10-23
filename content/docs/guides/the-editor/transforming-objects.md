---
draft: false
authors:
  - komatic5
title: Transforming Objects
weight: 1030
date: 2024-01-07T00:00:00.000Z
contributors:
  - komatic5
  - vexilo5
  - sethlai
description: The Edit tab contains tools for transforming objects through
  movement, flipping, rotation, warping, and scaling. This guide explains how to
  use these tools in order to control object properties in the editor.
tags:
  - Grade 0
  - Basic Editor
seo:
  title: How to Transform Objects in Geometry Dash
  description: How to use the traslation, flipping, rotation, scaling and warping
    transformations in Geometry Dash.
  canonical: ""
  noindex: false
---
{{< callout context="note" title="TLDR - What this guide covers" icon="outline/info-circle" >}}


- The edit tab is home to all the tools needed for transforming objects in the editor.
- The arrow buttons move objects in a particular direction by a certain amount according to their grid size.
- The flip buttons reflect objects about a certain axis.
- The rotation buttons turn objects by either predefined amounts or freely.
- The warp and scale buttons can grow, shrink, and skew objects.



{{< /callout >}}

- - -

Transformations are ways to manipulate 2-dimensional objects. The “Edit” tab in the editor contains all the tools you need for movement, rotation, reflections, and scaling.

{{< img src="https://lh3.googleusercontent.com/d/1PdgQ1eaUgEANsA0Bh7BelCczCFDLWXXW" >}}

# 1: Arrow Buttons

The **arrow buttons** **let you move objects around on the grid**. As you may expect, they move objects in the direction they point, so the up arrow moves objects upward for example.

The number in the middle of the arrow corresponds to the amount an object will move when the arrows are clicked. The arrows in the middle of the edit tab can change the amount an object moves:

* Triple arrow: **5** grid spaces
* Double arrow: **1** grid space (WASD)
* <span style="color: #FF1493"> Pink arrow: Default is **1 grid space**, but can be changed if button is **double-clicked**
* Large arrow split in two: **1/2** of a grid space
* Medium-sized arrow split in two: **1/4** of a grid space
* Small arrow split in two: **1/8** of a grid space
* <span style="color: #D3AF37"> Large yellow arrow: **1/15th** of a grid space (Shift + WASD)
* <span style="color: #D3AF37"> Medium-sized yellow arrow: **1/60th** of a grid space
* <span style="color: #D3AF37"> Small yellow arrow: **1/300th** of a grid space

As for the legacy edit menu, the one that came before update 2.209 (which can be toggled on in the settings), the arrow icon on each of the buttons depends on how much they move objects:

* Small arrow: **1/60th** of a grid space
* Single arrow: **1/15th** of a grid space (Shift + WASD)
* Single arrow split in two: **1/2** of a grid space
* Double arrow: **1** grid space (WASD)
* Triple arrow: **5** grid spaces

{{< img src="https://lh3.googleusercontent.com/d/1fDJmounKQRESy2q9mAICgOfK-lKZbdOP" >}}

A **grid space** is **the size of one square on the editor grid**. By default, most objects will have a normal grid size, but some objects have smaller grids (e.g. 0.5x, 0.25x). To have more control than that, click the "Grid" button at the top right of your screen.

Here are some example grid size conversions:

* 4x default grid: **120** units
* 2x default grid: **60** units
* 0.5x default grid: **15** units
* 0.25x default  grid: **7.5** units

{{< youtube xECWomz5xYk >}}

# 2: Flip Buttons

The **flip buttons** **reflect objects horizontally and vertically**. This is mostly self-explanatory, but it’s important to pay attention to flipping objects with abnormal hitboxes.

{{< img src="https://lh3.googleusercontent.com/d/1dGT9A9kHpR_Xn08tagfVPJOdz5C46yig" >}}

For example, if you want a slope to face in the opposite direction, you need to use the flip buttons. Rotating it 180 degrees will cause the hitbox to be **backwards**, which is hard to notice at a glance and is generally undesirable.

{{< img src="https://lh3.googleusercontent.com/d/1hwYVhlXhV1H2A361ejnasREM2ifOQYxW" >}}

# 3: Rotation Buttons

The **rotation buttons** **let you turn objects about their center**.

The rotation buttons are all labeled with large circular arrows, some with text on them:

* No text: 90 degree rotations clockwise or counter-clockwise
* “45”: 45 degree rotations clockwise or counter-clockwise
* “Free”: Precise rotations by dragging the circle that appears around the object(s). Note that the “Rotate” button to the far right does the exact same thing.

**Static objects** with NoTouch disabled can only be rotated in 90 degree angles; if you enable “Allow Static Rotate”, they will only visually change their appearance. **Non-Static objects** can be rotated using any of the rotation buttons, as well as the Free Rotate buttons.

{{< youtube QyKNGd7pfH8 >}}

Rotation can be very helpful for decoration if you want a shape to face a certain angle.

{{< youtube PhB2dU9y3-w >}}

It is also helpful for trigger setups if you want a group of triggers to activate at an equal distance, without needing to use Align X to get them in the right place.

{{< youtube vunEH4FTqjo >}}

# 4: Warp & Scale Buttons

**Scaling** **changes an object’s size and aspect ratio**, while **Warping** **changes its skew**. These are the three buttons in the bottom right of the Edit tab.

The “**Scale**” button with one horizontal line scales an entire object’s size. By default, it ranges from 0.5x to 2x scale, but can be expanded to 0.25x and 4x scale with the “Increase Scale” setting enabled. Additionally, if the lock button above the scaling interface is toggled off ("unlocked"), every selected object in a group will scale based on the center of the group. If it is on (locked), each selected object in a group will scale based on its own center.

The “**Scale**” button with a horizontal *and* vertical line scales an object’s horizontal and vertical size independently, just like a Scale trigger.

The “**Warp**” button (Ctrl+T) lets you transform an object to infinite size as well as skewing. Drag the circle in the middle to set the center for scaling and skewing. Then, use the side buttons to scale your object horizontally or vertically, the corners to scale both at once, and the side rectangles to skew. The circle outside the warp UI rotates it just like Free Rotate. The buttons above the warp interface do the following:

* Lock button: Retains the object’s aspect ratio when using the corner buttons
* Box with line connecting the corners: Automatically anchors the center circle to the opposite side or corner from which you are warping
* Grid: Snaps anchors to grid
* Rotate: Lets you rotate the anchors, but not the actual object

{{< youtube 8OZdomCo88I >}}
