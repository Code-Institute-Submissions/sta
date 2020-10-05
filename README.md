# Sky Trackers Association

Table Of Contents

- [Overview](#overview)
- [Design](#design)
    - [UX](#ux)
    - [Visuals](#visuals)
- [Tech Used](#tech-used)


## Overview

Sky Trackers Association goal is to promote astronomy to young audience. Raising curiosity about what's beyond our 
atmosphere, understand better our planet and how it is unique.


## Design

This web app is dedicated to teenagers and their parents joining their night sky explorations. I've choose to build a
sci-fi look with a light weight interface. The idea is to give a feeling of using high tech console to access information without 
distracting the young audience from the content and focus on the learning purpose. Avoid information and visual overload.  

### UX

**Personas**

- Evan:
	Teenager with curiosity for the night sky and what’s up there in deep space !

- Eleanor:
	Eleanor is a young female teacher in mid school. She wants to use materials accessible to young audience and high quality 
	images to raise her class interest in astronomy, related sciences and what it leads to. Hopefully will raise curiosity of some to find out more

**User Stories**

- As Evan I want to know more about the moon cycles so I can appreciate better its changes every night.  

- As Evan I want to learn about observation techniques to be able to pinpoint stars from a map by myself.

- As Evan I want to learn about instruments setup so that I can enjoy deeper the night sky with my telescope.  

- As Evan I want to find information about Jupiter's moons so that I can try to get a deeper knowledge about satellites 
and compare with our Moon.


- As Eleanor I want to introduce the solar system to my class for them to catch the bigger picture of life on earth and 
how it is unique.  

- As Eleanor I want to poke my students with an experience about what it is to study in astronomy.  

**Wireframes & prototyping**

I've [sketched](./ux_documentation/sketches) few concepts that answer these main guidelines before building an 
[animated wireframe prototype](https://xd.adobe.com/view/28ab82c9-8297-45c1-6aff-7a57d62f62a1-5e9a/?fullscreen) with AdobeXD. 
PDF version [here](./ux_documentation/sta_prototyping.pdf).  

[To top](#sky-trackers-association)

### Visuals

**Color Scheme**  

The colors are split in 3 categories:
- Background  
    Dark greenish-cyan desaturated color. Graphics/fonts should be dimmed not to take over the main UI. Coming from 
    futuristic digital display, gradient to purplish color will introduce some interesting yet subtle contrast in the bg color.
- Main UI / HUD  
    Warm color range to contrast with the background and echo with our sun's light temperature.
- Interactive elements  
    Bright and highly saturated colors standing out in the HUD to guide the young audience with available interactions.

| Background  | HUD | Interactive |
| ------------- | ------------- | ------------- |
| ![#202b34](https://placehold.it/60x30/202b34/202b34) `#202b34` cyan  | ![#BF702B](https://placehold.it/60x30/BF702B/BF702B) `#BF702B` main | ![#4181f1](https://placehold.it/60x30/4181f1/4181f1) `#4181f1` main |
| ![#273835](https://placehold.it/60x30/273835/273835) `#273835` greenish  | ![#FCF9DD](https://placehold.it/60x30/FCF9DD/FCF9DD) `#FCF9DD` light warm | ![#F15641](https://placehold.it/60x30/F15641/F15641) `#F15641` secondary |
| ![#19191c](https://placehold.it/60x30/19191c/19191c) `#19191c` dark blueish | ![#9FEBF3](https://placehold.it/60x30/9FEBF3/9FEBF3) `#9FEBF3` light cool |  |
| ![#0e0f1d](https://placehold.it/60x30/0e0f1d/0e0f1d) `#0e0f1d` deep sky |  |

**Graphics**  

Graphics should have a futuristic / sci-fi look without being complex. It is not a movie screen graphics but information
display to young audience therefore should not contain too many distracting elements that make the reading and learning harder.  
Same goes for animations and transitions.

**Photographs & schematics**

High quality photographs are necessary to engage young audience. They should be inspiring and relevant to the section they illustrate.  

**Fonts**  

- Logo  
    Logo should represent the vision of STA.  
    I chose [Bellefair](https://fonts.google.com/specimen/Bellefair) for its elegant and timeless latin typeface with a
    light weight expressing humility and patience.
- Titles  
    Strong body font that stands from the main text without adding too much weight nor complexity.  
    [Barlow Condensed](https://fonts.google.com/specimen/Barlow+Condensed).
- Main text  
    Easy to read font without serif. [Roboto](https://fonts.google.com/specimen/Roboto) is almost inevitable.
- Graphic fonts  
    Preferably hard to read futuristic font as it is not intended to be read but part of HUD graphics. Title font could
    be used, desaturated and dimmed. Else remove all graphic text from HUD. I've chosen [Saira Condesed](https://fonts.google.com/specimen/Saira+Condensed)
    as supporting gfx font.  


[To top](#sky-trackers-association)


## Tech Used

- [SASS](https://sass-lang.com) for styling.
- [Bootstrap4](https://getbootstrap.com/) to set up our basic template layout.
- [jQuery](https://jquery.com/) library is required for Bootstrap4 and used for DOM manipulation and subtle animations.  


### Software

- [PyCharm](https://www.jetbrains.com/pycharm/)  
    My favorite IDE even for Front-End projects.
- [GitKraken](https://www.gitkraken.com/)  
    Handy to visualize the commit tree, stashes, diff split view etc. It is an essential tool in my workflow along with PyCharm VCS.


[To top](#sky-trackers-association)
