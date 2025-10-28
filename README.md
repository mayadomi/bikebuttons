# bikebuttons
Concept/project to build a device that captures an event type and GPS location through coded buttons mounted on the bicycle.

## Problem/Scenario

Whilst riding, both adverse and positive events occur. Examples of negative events include:

Vehicular:
- close passes by vehicles
- vehicles blocking/obstructing bike lanes/paths
- near misses at intersections
- abuse/throwing items

Pedestrian:
- dogs on long leads/no leads
- blocking bikepath
- stepping out/stopping suddenly

Other cyclists:
- close/fast passing
- near misses at intersections
- abuse

Environmental:
- blockages (eg fallen trees/branches)
- detours/poor signage/routes
- unsafe design (eg bike lane ends with no safe alternative)

Positive interactions include:
- waves/smiles
- encouragement/riding alongside
- cycling friendly designs - eg bike racks, water stations, maintenance stations

When these events occur, it can be challenging to capture the location and nature of the event in realtime - either because of a safety risk (eg because you're in middle of an intersection, or trying avoid escalating conflict etc), or because there's not a convenient/safe spot to stop and capture details in the moment. 

People are also unlikely to retrospectively capture events, due to time/effort required. And whilst onboard cycling 'dashcams' exist and are invaluable for evidencial proof of events, they don't capture discrete data points such as location without significant post-processing of video by either a vendor or user reviewing footage. 

## Mission

To create a portable device that can be fitted to most bicycles around the stem, handlebars or top tube and contains an interface of tactile colour/braille coded buttons. 

Each button is coded to a particular event type (eg 'close pass') and on press, will capture a timestamp, GPS location and the event type; and stored either in a micro sd card or (ideally) synced directly with a service on user's phone.

The device blueprint/construction should:
- be simple enough that it can be open-sourced/people can build their own
- small enough to fit on a bike without obstructing/affecting safe cycling
- robust to withstand sun/UV and moisture exposer
- sufficiently powered to run on rides/excursions of up to 6 hours.

## Vision

The end data result would be an anonymised crowdsourced spatial dataset that can hopefully capture the experience of cyclists and highlight both problem-spots and successful cycling environments; to better guide prioritisation of cycling infrastructure/programs and identify the features that make for successful cycling experiences.

## Execution/Blueprint Concept

Components:
- arduino nano
- neo 6m gps unit/GSM module
- individual buttons; or, remote controller.
- battery
- bluetooth (or micro sd card)

Housing:
3D print housing

Services/software:
Point-based spatial service

