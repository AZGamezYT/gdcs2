---
draft: false
title: Trigger Systems
weight: 1130
date: 2024-01-15T00:00:00.000Z
description: This guide explains how you can use Trigger Channels, Trigger Order, and Trigger Tracing.
authors:
  - illusion2
contributors:
  - illusion2
  - vexilo5
tags:
  - Grade 0
  - Advanced Editor
seo:
  title: How to Use Trigger Channels & Tracing in Geometry Dash
  description: Trigger Order and Trigger Channels are often misunderstood. This guide explains what they do and how to use them properly.
  canonical: using-channels
  noindex: false
---

{{< callout context="danger" title="This guide is outdated" icon="outline/info-circle" >}}

With update 2.209, a lot of changes were made to the editor. This guide on its current state holds up until 2.207, and is currently being updated.

{{< /callout >}}

{{< callout context="note" title="TLDR - What this guide covers" icon="outline/info-circle" >}}

* Trigger Order is an important mechanic used to make your gameplay go in order when working with arrow triggers, speed changes, and more.
* Trigger Channels are used in order to make sure your triggers activate correctly if you’re using arrow triggers.
* Trigger Tracing ...

{{< /callout >}}

- - -

# 1: Trigger Channels

**Trigger channels** are a new 2.2 feature that **allow for the correct timing of trigger activations when arrow triggers are involved**. In order to understand trigger channels, we first need to go over trigger order.

## Trigger Order

**Trigger order** **allows for gameplay objects to activate in the correct order**. These objects include anything that affects the green music line when you play the song in the editor, such as arrow triggers and speed changes. It’s important to use trigger order rather than applying “Touch Trigger” to everything because the triggers no longer rely on where the player touches the trigger’s hitbox, which might make your gameplay out of sync.

When selecting a trigger and clicking on {{< img src="images/GDEmotes/Triggers/Arrow.png" class="emote" >}} Edit Group, a menu appears. We only need to pay attention to the two counters below the Z layer buttons.

{{< img src="https://lh3.googleusercontent.com/d/1RZ3ho1phswAgN7KSBZYFjIIuBpS4XTZ8" >}}

The “ORD” counter refers to the trigger order. The number in the counter dictates the order that object will activate in. For example, an arrow trigger with order 1 will go first, then 2, and lastly 3. However, your numbers don’t have to go strictly one after another; you could use orders 1, 4, 5, and 8 and it would still work, provided that the numbers keep increasing.

Keep in mind that reversed orbs and teleport orbs all affect the music line but are heavily player-dependent, which might desync your gameplay despite being ordered.

{{< youtube 0soHKShq800 >}}

{{< callout context="caution" title="Important" icon="outline/info-circle" >}}

Using trigger order on arrow triggers only works if you enable “Change Channel.” Select the arrow trigger, click Edit Object, and check the corresponding box. We don’t know why you need to enable this, but the level will break otherwise.

{{< /callout >}}

{{< img src="https://lh3.googleusercontent.com/d/1g_eZCvV6P8ZfTyyalsQn2AM6VOJGYaDY" >}}

## Trigger Channels

Using the menu above in the {{< img src="images/GDEmotes/Triggers/Arrow.png" class="emote" >}} arrow trigger, you can change the target channel of the level. The level constantly runs on a certain channel, and triggers will only be able to activate *if their channel matches the current channel*.

To change the level’s channel, open the menu of the arrow trigger, enable “Change Channel,” and select your channel using the counter that appears below.

You can set the channel of triggers with the “CH” counter in the {{< img src="images/GDEmotes/Buttons/EditGroup.png" class="emote" >}} Edit Group menu, next to the “ORD” counter. If you ever wonder why your triggers aren’t activating, check to make sure they’re on the correct channel. *Only arrow triggers can change the level’s channel*, not reverse triggers or reversed orbs.

{{< youtube OZnDpqJ8T0M >}}

{{< callout context="note" title="Note" icon="outline/clipboard-text" >}}

Note: Both orders and channels require the “EDP” or "Playtest" box checked in the Edit Group menu.

{{< /callout >}}

# 2: Trigger Tracing

To be added