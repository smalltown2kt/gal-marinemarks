# Marine Marks Set

Copyright 2025 smalltown2kt

## Contents

This project contains a set of marine marks (spars/posts) for laying out your maritime areas, rivers, marinas, harbours, and other coastal areas. They are designed to be [IALA compliant](https://www.iala.int/product/r1001/ "IALA buoyage system specification"), ensuring your project is technically correct (the best kind of correct).

![Demo set of all](https://raw.githubusercontent.com/smalltown2kt/gal-marinemarks/refs/heads/main/img/Selection1_full.png)

Set includes:

* Channel 'lateral' marks
* Preferred channel lateral split marks
* Safe water ('fairway') marks
* Special marks
* Isolated danger marks
* Cardinal marks (North, South, East and West)

Each marker post is set up in a scene in the ./parts/ folder:

* Two sets of marker posts are provided. One is cyclindrical and the other square-profile (chamfered) posts.
* Where System A or B is not specified, the same appearance applies to both areas.
* All posts are transformed to a notional water line at (0,0,0) and so extend underwater. Texture includes underwater 'wear' and fade out at the waterline.
* Poly counts vary depending on the specific item but are all <1500 poly each.
* The material is provided with a normal-mapped texture to emulate a worn wooden painted surface.
* Colliders set up on each.

A series of 'demo' scenes have been included which were used to generate the preview images, and which show you how you can use them with your water and ground meshes. Reminder, y=0 is the water level, not your ground level!

## IALA System

The [International Organization for Marine Aids to Navigation](https://www.iala.int/) is the international body which specifies the style, visual and requirements for buoys and marine navigation equipment.
For historic reasons there are two systems:

* IALA System A: Used by most of the world. Port is red and starboard is green. (e.g. image below)
* IALA System B: Used by the Americas and parts of East Asia. Starboard is red and port is green.

![IALA System A set](https://raw.githubusercontent.com/smalltown2kt/gal-marinemarks/refs/heads/main/img/Selection2_full.png)

## Support

If you find these assets useful, I'd love a coffee!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B51K7DSL)
