+++
date = "2020-03-24T00:13:20-07:00"
description = "Digitalization of a board wargame for the British Royal Navy"
title = "SERGE. SERious Gaming, Evolved"
icon = "route"
+++

<div class="at-a-glance">

At a Glance | <i class="fa fa-th-list"></i>
--------|---
Domain  | Simulation - Wargaming - Defense
Type    | UX research (15%), UX design (85%)
Skills  | User flow, information architecture, wireframes, prototypes, workshop
Tools   | AdobeXD (1st phase), Figma (2nd phase)
Duration| 1+ year (on-going)

</div>

[Serge](https://sites.google.com/deepbluec.com/serge/) is a browser-based war-gaming tool used by the British Navy. 

## Objectives:

* Provide a **platform for game designers** to create any type of wargame scenarios
* Design a user-friendly **web interface for players** to interact
* Record every in-game move and interaction for **future analysis**

<br/>
{{< figure src="/images/serge-player-ui-channels.png" title="Player UI - communication channels" >}}

## Target Users:

* Wargame designers and analysts
* Navy trainees to high-rank officers

## Challenges: 

* Only one interface to support multiple functions: mapping, communications and admin
* Multiple displays: touch table, interactive whiteboard, laptop screen and large monitor
* Capabilities need to be as close to reality as possible: this is used for training or simulation purposes, not for fun.


## Team members

### Core Team
* Product owner & developer (PO)
* Lead developer (LD)
* UX designer (UX - me)


<br/>
Plus: additional developers (up to 3), graphic designer (as needed)

## Process: 

### First phase: basic framework & communication channels

I worked closely with the product owner on the first steps:

#### - User flows for game designer, player, umpire

#### - Game admin architecture

{{< figure src="/images/serge-game-designer-overview.png" title="Game designer UI - wireframe" >}}

{{< figure src="/images/serge-admin-ui.png" title="Game designer UI" >}}

#### - Layout of player & umpire UI: 2 different and flexible options

{{< figure src="/images/serge-initial-layout-options.png" title="2 options for general layout" >}}



#### - Low-fidelity wireframes of communication channels

{{< figure src="/images/serge-blue-force.png" title="Player UI - wireframe" >}}

Both PO and lead developer developped the back-end and front-end. A graphic designer suggested different high-fidelity designs before we settled on a version of a material design dark theme.

The first release was tested during a wargame in July 2019. PO and LD could attend thanks to their security clearance (I could not unfortunately). They were able to observe the game in real-time and identify additional needs as well as the pain points users were facing. 

{{< figure src="/images/serge-player-ui-channels.png" title="Player UI - communication channels" >}}


### Second phase (on-going): mapping capabilities & task groups

A first workshop allowed us to review the way players and designers interact with a map and to discuss the best options to implement digital mapping. 

A very quick implementation (one month) followed by testing with trainees gave us valuable feedback to refine the mapping features. We are now working on adding task groups.

{{< figure src="/images/serge-umpire-view.png" title="Umpire UI - Map view of all forces - Mockup" >}}

{{< figure src="/images/serge-mapping-work-in-progress.png" title="Umpire UI - Map view - Web interface - work in progress" >}}

