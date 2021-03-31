---
title: Localization
module: 11
jotted: false
toc: true
math: false
topic: Localization
---


The most obvious quality of a sound in space is its _position_. When you listen, you are able to determine where a sound is positioned by our ability to _localize_.

This ability to localize extends to 360° immersive sound field. The brain, working with the ears, are capable of identifying the location of sounds on the lateral/horizontal plane 360° around you (left-to-right, often described in terms of the _azimuth_), but also on the vertical plane (elevation). In addition to this ability, the brain is also capable of making estimates of a sounds _distance_, or how close/far a source is.

## General Info on How We Localize

Our ability to localize sound (or to place its position in space) is possible through both the fact that we have two ears placed on either-side of our head, along with how a sources sound-waves move in a specific space.

With respect to localizing in the lateral plane, there are two distinct ways that our brains localize sound.

### Interaural Time Difference (ITD)

Interaural Time Difference (ITD) is the amount of time delay between a sound source entering the ear that is closest to the sound (ipsilateral) between when it enters the ear furthest from the sound source (contralateral). Our brains calculate that a sound that enters one ear before the other, must be closer to that ear; I.E. on that side of the head. The amount of delay in time between when a sound reaches both ears, helps our brains estimate where on the lateral plane the sound source is.

![Example of a sound source entering an ipsilateral then contralateral ears](../imgs/HRTF.svg "Example of a sound source entering an ipsilateral then contralateral ears")

ITDs generally help us localize sounds that contain lower frequency content (less than 1kHz to 1.5kHz).

### Interaural Intensity Difference (IID)

Interaural Intensity Difference (IID) (also sometimes referred to as Interaural Level Difference (ILD)) is the amplitude or level difference that a sound exhibits between both ears. A sound that is louder in one ear than the other is estimated to be closer to that side of the head.

Intensity differences occur in frequencies above 1.5kHz. This is the frequency range where the frequencies are short enough as to be blocked by our actual head. This blockage of the head causes these sounds to be softer on the contralateral side (far side) of the head.

#### Amplitude-Based Panning

Most DAW's employ (by default) panning algorithms that are based on this idea of amplitude differences. A sound that is louder on one side of the stereo field than the other is perceived by our brains as being "on that side".

#### Front-Back Confusion

As you are likely starting to assume, these two cues that our brains use allow for great localization between 0° (this is a sound source directly in front of us) and +/- 90° (directly to either side of our head). However, these cues can cause our brains to make mistakes or become confused about whether a sound is 'in-front' or 'behind' us. It is in fact common for our brains to mistake a sound that is in-front or behind to mistake it for being the other. Our sense of sight assists in this problem, by supporting (or testing) our brains guess by looking for the sound source.

### Vertical Location

In addition to our ability to localize on the horizontal plane, we can also localize on the vertical plane. This is a complex topic, but simply put, the way that sound hits and enters our ear's _pinnae_ (the ridges in the outer ear) allow our brains to make inferences as to the vertical angle of sound source.


## Information About Localization

During our soundscape work earlier in the semester, I asked you on multiple occasions to try and localize where sonic events were occurring in space.

The placement of individual sonic events to each other offers the listener information about the relationship of these events to each other. Events that occur 180° degrees apart from each other are more likely to be perceived as separate, as well as conversational or adversarial. Whereas two sonic events that happen close to each other (such as less than 45°), are more likely to be perceived as complementary. Events that occur in the same location are likely to be perceived as sounding from the same source.


## Distance

In addition to our ability to localize position horizontally or vertically, our brains also make estimates as to a sound source's distance.

However, this is a difficult task, as distance is inferred through the qualities of the sound itself, and not through the way the sound enters our ears.

### Loudness Differences for Distance

As a simple example, louder sounds are often estimated to be closer than soft sounds. So these types of cues are not particularly helpful.

As a sonic artist and sound engineer, this knowledge allows you to know that mixing one sound louder than another sound will cause that louder sound to appear to be closer, as well as more important to a listener.

### Room Cues for Distance

Another way that our brains can infer some sense of a sounds distance is through the sounds perceived interaction with the acoustic qualities of a space.

As an example, if we know we are in a large space, such as a gymnasium, then the amount of direct sound versus the reverberant sound can offer our brains some cue as to how close or far a sound source is.

{% comment %}
Need some figure/image examples
{% endcomment %}

Especially in sound design, audio engineering, and sonic art, the use of reverberation is critical in helping offer distance and space cues to listeners.
