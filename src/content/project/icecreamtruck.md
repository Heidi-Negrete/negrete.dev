---
title: "Just an Ice Cream Truck"
description: "Control an ice cream truck on an urgent mission, using an arduino board as an external controller. Built using Arduino Uno, Blender, and Unreal Engine 5."
heroImage: "/icecreamtruck.png"
pubDate: "Dec 14 2024"
tags: ["Unreal 5", "Arduino", "Game"]
---

You must deliver ice cream to your destination before it's too late! You're just a monkey, but it's just an ice cream truck, how hard could it be?

I made this vehicle simulation game in Unreal Engine 5 and built a custom game mode that uses an external controller built around an arduino microcontroller.

## Play

<a href="https://angelic-garbage.itch.io/just-an-ice-cream-truck" target="_blank">Download</a> the game from itch.io. In this public release, you play with keyboard & mouse or standard playstation/xbox controller.

## Demo Videos

- <a href="https://youtu.be/Hjc5tV3f0QY?si=WuM0q9pFDS251BYQ" target="_blank">Gameplay Demo</a> using the Arduino game mode and Arduino Controller.
- Early <a href="https://youtu.be/Zl43jH7CGN8?si=a84laTaDrW_uu66t" target="_blank">Gameplay Demo</a> with keyboard & mouse.
- Level Design Testing <a href="https://www.youtube.com/shorts/Zvw_w7rCciU" target="_blank">Short</a>.

## Dev Log

Read about the development process in my devlog series:

- <a href="https://medium.com/angelic-garbage/just-an-ice-cream-truck-devlog-part-1-ffe53b77d7b6" target="_blank">Requirements, Brainstorming and Planning</a>
- <a href="" target="_blank">Development</a> (WIP, check back soon.)
- <a href="" target="_blank">Release and Post Mortem</a> (WIP, check back soon)

## Software & Technology

- Unreal Engine 5 (Blueprints)
- Blender (3D Modeling and Texture Painting)
- Arduino IDE (Arduino Uno Microcontroller)
- Figma (Design)
- Trello (Planning)
- OBS, Da Vinci Resolve (Recording and Video Editing)
- Adobe Photoshop, Procreate (Art and Animations)

## Arduino Controller

![A game controller made with an arduino uno, wearing googly eyes.](/arlan.jpeg)
The published version of the game does not include Arduino Mode, however, if you would like to build your own controller for a game of your own it is a great beginner electronic project! Information about how to build the controller, including the sketch and electrical diagram, and how to integrate it into an Unreal Engine product can be found on my <a href="https://medium.com/tech-tutors-tips/build-an-arduino-controller-for-your-unreal-5-game-v1-a9a081fe3990" target="_blank">how-to blog post</a>.

## External Resources

- <a href="https://github.com/videofeedback/Unreal_Engine_SerialCOM_Plugin" target="_blank">SerialCOM</a> Unreal plugin (Simplifies communication management between the microcontroller and the game engine)
- Sound effects by <a href="https://nox-sound-design.itch.io/essentials-series-sfx-nox-sound" target="_blank">Nox_Sound_Design</a>, CC0.
- Music is by <a href="https://sirental.itch.io/farming-game-music" target="_blank">Sirental</a>, Creative Commons Attribution v4.0 International.
