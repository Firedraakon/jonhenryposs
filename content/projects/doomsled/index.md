---
title: "Doomsled MkII"
weight: 1
draft: false
description: "Why walk on ice when you can roll?"
date: 2026-03-15
slug: "doomsled"
tags: ["ice", "ev"]
layout: "simple"
---

<hr class="bold-divider">

- [Introduction](#introduction)
- [Frame](#frame)
- [First Atttempt and Subsequent Problems](#first-atttempt-and-subsequent-problems)
- [Redesign](#redesign)
- [First Rides](#first-rides)
- [Major Battery Upgrade](#major-battery-upgrade)
- [Winter 2026](#winter-2026)

<hr class="bold-divider">

## Introduction

<div class="blue-highlight">

This is the MkII build; see the original [Dane Kouttron](https://transistor-man.com/doomsled.html). Built in collaboration with the venerable [Chris Evagora](https://evagor.ac/post/projects/doomsled/).

MITERS has historically done an occasional frozen lake adventure, but in 2023 there hadn't been one for years. The initial pitch for a new generation of ice vehicles was an ice boat, but that eventually evolved into an ice luge. The Doomsled MkII is loosely inspired by the original Doomsled, but moved away from certain speed/safety limiting features like the face-in-the-direction-of-travel. The end result is something of a cross between an ice luge and a recumbent tadpole tricycle.

Steering is foot controlled through a bogey, throttle and (the suggestions of) brakes are applied through grips at the seat. Also, yes that's an MBTA seat. 

{{< screenshot src="doomsledmodern.jpg" alt="Example image description" >}}

</div>

<hr class="blue-divider">

## Frame

The frame was designed around the few parts we actually had, which was mostly a gigantic, stainless steel shaft that's been sitting in the corner of the shop for the better part of a decade and a trailler wheel we found in the loading dock. We also got some steel tubing donated from the builder of the original Doomsled.

{{< screenshot src="ogframe.jpg" alt="Example image description" >}}

The steering works something like a skateboard. The angle of the head tube creates dynamic stabiliy and the rigid bogeys mean the frame leans into turns even while maintaining three points of contact. This feels cool as hell 

{{< screenshot src="steering.jpg" alt="Example image description" >}}

<hr class="blue-divider">

## First Atttempt and Subsequent Problems

The first version worked okay. The steering geometry worked great and achieved the exact kind of dynamic stability we were looking for. However, everything was floppy. Speed wobbles developed somewhere around 10-20mph and, while it was possible to accelerate through them, it was also getting close to throwing riders. We determined the problem derived from the massive weight of the rear wheel and axle and the relatively low stiffness frame and steering. While the geometry was right, the entire steering assembly was undersized by quite a bit. 

<hr class="blue-divider">

## Redesign

I wasn't taking any chances with the front steering so I redesigned the front with a heavily braced head tube with proper tapered bearing. We built as much as we could with 1/4in steel plate cut on a barely funcitonal waterjet. I welded and Chris machined. Despite two noticiably different sized amazon bearings, the head tube fit was still good. 

{{< screenshot src="newfront.jpg" alt="Example image description" >}}

We also beefed up the linkages after a bearing failure. Ideally, the pedals and pivots would also be improved, but they're annoying to dissassemble and the whole thing was getting too heavy to keep dragging upstairs to the welding room.

{{< screenshot src="frontlinkage.jpg" alt="Example image description" >}}

This solved most of the steering slop but it was also around here when I realized I had very little intuition for torsional stiffness of flat tube frames and the frame iself was still floppy. We were able to stiffen up the frame some by "skinning" it with welded steel sheet on either side of the tube. Adding material as far away from the geometric center is mathematically best for increasing stiffness, but there's still only so much to gain welding on plate an inch away from center. The downside is the downside is the whole vehicle is still a bit squirrely, but the upside is the floppy frame works as a fairly effective suspension system and the ride is remarkably smooth. You can see us bouncing in the videos. 

<video controls playsinline width="100%">
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<hr class="blue-divider">

## First Rides

{{< youtubeLite id="H-JZ_1kkQL0" label="riding test" >}}
{{< youtubeLite id="d3tMZuaDbBY" label="riding test" >}}

Definitely an absolute blast to ride. Stable at speed, super solid control even on drifts. We did have cutouts at max speed and only got up to around 40mph. At the time, we thought this was due to bad controller settings. Either way, it left us with plenty of battery life to screw around towing people after a few races. 

{{< youtubeLite id="3Lg1APSj0mM" label="riding test" >}}

## Major Battery Upgrade 

Chris put together the original battery from cells we bought off of batteryhookup.com. These were remarkbaly cheap, but had to be sorted by internal resistance and their performance wasn't exactly thrilling. 

In the end of 2025, the agricultural drone company Guardian Agriculture (actually also kind of a MITERS startup) went under and auctioned off everything that hadn't already been carried off. That's how we came to own a drone test stand battery pack with about a third the ESR. Which is to say, our battery would no longer be the bottleneck. 

{{< screenshot src="newbattery.jpg" alt="Example image description" >}}

Of course, this battery was far too large to mount behind the fender like before, so I bolted it to the top. Chris revamped the electronics and I made a few mechanical upgrades. 

{{< screenshot src="fender.jpg" alt="Example image description" >}}

I spent a couple of hours building a steel box for the battery and a mud flap to keep the water off of it. Finally, I added a suzuki motorcycle damper to the front steering to help damp out any more speed wobbles we might get with the added mass of the battery in the rear. We never ran without it, so it's unclear if the damper was actually effected. But either way, we never had speed wobble issues. 

{{< screenshot src="lolspeaker.jpg" alt="Example image description" >}}
{{< screenshot src="speakerpanel.jpg" alt="Example image description" >}}

In a move of absolute genius, Chris also mounted a couple of speakers for sound effects. 

## Winter 2026

The doomsled ran again this winter. Unfortunately, we didn't get everyone out there until the last possible date, so the top of the ice was covered in slush. 

{{< screenshot src="donut.jpg" alt="Example image description" >}}

We were perhaps the fastest on the ice for a brief moment before I hit a patch of slush and got thoroughly bogged down. The limit this year was the motor itself overheating.