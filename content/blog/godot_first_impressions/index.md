+++
title = "godot first impressions"
date = "2023-10-29"
description = "A retrospective on learning the Godot game engine by building a SNES Tetris clone."
tags = [
    "gamedev", "godot"
]
draft = true
+++

I've decided to try out the [Godot game engine](https://godotengine.org/).

In the wake of [missteps from Unity](https://finance.yahoo.com/news/unity-responds-huge-backlash-over-131515630.html), Godot has been promoted as a shining example of game engine development done right. Perhaps Godot has the chance to pick up new users and follow in the footsteps of other successful open source projects, like [Blender](https://www.blender.org/). 

The best way to learn a new tool is by making something, so I made a clone of the [SNES version of Tetris](https://www.youtube.com/watch?v=-FAzHyXZPm0). It's a small slice of the full game that drops you into the A-Type mode.

You can try it out by clicking the button below! Just a few disclaimers:

* The download size for the game is 28.5 MB
* Only keyboard is supported. The game won't respond to input on touch devices.
* These are the controls:
    | Action     | Right Handed | Left Handed |
    | ---------- | ------------ | ----------- |
    | Move L     | Left Arrow   | A           |
    | Move R     | Right Arrow  | D           |
    | Fast Drop  | Down Arrow   | S           |
    | Rotate CW  | X            | Period (.)  |
    | Rotate CCW | Z            | Comma (,)   |
    | Restart    | R            | R           |
    | Mute       | M            | M           |
    | Pause      | P            | P           |

{{< include_html "content/blog/godot_first_impressions/tetris_embed.html" >}}

### does godot deserve the hype?
