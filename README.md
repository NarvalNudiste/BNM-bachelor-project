# probable-umbrella

## Bachelor project 2018

### Abstract

*This school project, in collaboration with Bienne's Nouveau Musée, aims to develop a small educational serious game in virtual reality oriented towards childrens and young visitors.
As the exhibition will feature original work from an invited painter representing a palaeolithic life scene, visitors will be able to interact with a virtual representation of objects from this era which would be way too fragile to manipulate in real life and replace them in a painting.
The intent is to educate players on said objects with an entertaining experience.*

### The game

The players are set in a replica of Bienne's Nouveau Musée. They are presented with a table on top of which 5 distinct palaeolithic objects are laying. In front of them is a large painting picturing the use of said objects in a real life scenario.
The objective of the game is to match each object by replacing them in the correct area of the picture. By doing so, objects will "fade" into the picture, reveiling the original work of art.
Objects will be accompagnied by a short description (maybe sound) provided by the Museum.

### Specifications

* Unity implementation
* Movement in a restricted area
* Objects interactions
* Matching mechanic (realistic type of render)
* 3D model of the room
* UI (extra-diegetic)
* Sound (if provided by the client)
* Reset mechanic
* Feedback effects
* Installation

#### Data collection

* Room visit, photographs - done, 28.02.2017

#### Mechanics

* Setup VR in unity - done
* Basic testing room - done
* Grabbing custom models - done
* Opening doors mechanic - work in progress
* Custom object classes (Data structure ?)
* Custom models colliders - (simplified mesh colliders work pretty well)
* Movement (Teleportation) - done, maybe not needed
* Area matching with held item
* Reset button
* Information overlay
* Sound triggering
* Feedback effects
* (Opt) Breaking objects / Respawning objects
* (Opt) Third-person visualization (Unsure if doable in Unity)

#### Visual

* Display cabinet model
* Museum room model
* Object models
* Lightning
* Post-processing
* (Opt) 3D painting
* (Opt) Render style (cartoonish)

#### Documentation

* User manual
* Actual installation
* Report

#### Timeline

* 20.02.2018 - VR tests at home, setting up the steamvr plugin
* 23.02.2018 - Starting implementing showcase mechanics
* 26.02.2018 - VR tests at home with placeholders
* 28.02.2018 - Room visit, photographs
* 29.02.2018 - Started room 3d model
* 06.02.2018 - Basic room model finished, will do for testing
* 08.02.2018 - Solved lightning issues / Imported the room model / Materials fixing
* 15.03.2018 - Custom model grabbing mechanics is okay, a little hack has been used to handle the highlight mechanic for complex models composed of more than one mesh
* 20.03.2018 - Matching mechanics (Gizmos used as placeholder), implementing callbacks
* 23.03.2018 - Meeting
