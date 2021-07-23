---
title: Track Groups
module: 11
jotted: false
toc: true
math: false
topic: Track Groups
---

Another approach that can be taken when applying the same signal processing plugins to multiple tracks involves grouping those tracks as a "track group," creating a "sub-mix," or a "sub-bus" (_all three names are appropriate, depending on the DAW. We will refer to these as "track groups", as that is the name Reaper uses_).

A track group takes multiple tracks, and "groups" them together. This then means that each track that is part of the group is "bused" through the group track before being sent to the master bus.

Regardless of domain, style, or content type, this is a common approach to take when working on large sessions of mixes. As an example, when working on a large music mix, you likely want to create groups representing the drums, guitars, lead vocals, backing vocals, synths/keys, etc. In each of these groups all of the associated tracks are sent to the main group track, where we can apply signal processing to the combined signal.

More significantly though, you can now alter the gain or amount of this group being sent to the master bus as a group (rather then having to adjust each track individually). Likewise, if you want to mute or solo a group, this group track makes it easier to do so.

<div class="embed-responsive embed-responsive-16by9"><iframe class="embed-responsive-item" src="https://www.youtube.com/embed/YSMZD6d1ww4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

## Creating a Track Group

To create a track group in Reaper;

1. Create a new track that will be the main group track.
2. Label the track appropriately.
3. Click and drag each track onto the master group track. (This will cause the track to "indent" under the master group track). **{ NOTE: }** This will have to be done in the TCP not the mixer window.

Now you can affect all of the tracks in the group together.

![Example of creating a track group.](../imgs/group-creation.gif "Example of creating a track group.")
