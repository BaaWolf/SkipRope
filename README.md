# Digital Skip Rope

We decided to create an Imaginary Skip Rope game at Global Game Jam 15 for theme - "What do we do now?".

We think this is interesting because unlike traditional Skip Rope our game is a little more forgiving - there is a relatively low risk of injury since you can jump to any height, we could introduce dynamic balancing to give new players an advantage, you could play it remotely over the Internet, there's no right and wrong answer (you're not out when you get hit), and best of all, you use your imagination.

We simulate the rope using verlet integration - so the game is authentically reproducing a rope behind the scenes. Players can collide with the rope when it is at the low point in the travel, unless of course they jump.

We integrate to find the position of the blue/red controllers which we use to spin the rope. To detect when the central players have jumped we measure the magnitude of the movement of the white controllers.

Players are given a "rolling start" by letting the end players "arm" the PlayStation Move controllers once players are ready. Each game lasts only twenty seconds - the best player is indicated by giving them a green light, the other, a red light.

What Do We Do Now? was the theme to GGJ15. As players on both sides of the rope - we become a little bit of the game engine - what do we do now? Do we play nice or do we go fast?

Programmed by Gavin Wood (Newcastle University), and John Shearer (Lincoln University) who was also facilitating the Game Jam.

Thanks to Amber van de Rest and Nick Harbour for playtesting our game. http://thp.io/2010/psmove/ for their PS Move API, and http://games.lincoln.ac.uk for hosting the event.

## Licenses

All my software is provided 'as-is', without any express or implied warranty. In no event should the author be held liable for any damages arising from the use of this software.

In this folder you can find Third Party software. Please note I have added my own library projects to bring this code into my build and these are therefore edited versions of the software.

## Third Party software:

All Third Party software is provided 'as-is', without any express or implied warranty.

In no event should the individual authors of this software be held liable for any damages arising from the use of this software.

See readmes in the folders and/or source code for the author’s license.

Please refer to the author's original sites for unedited and clean versions.

PS Move API - ttp://thp.io/2010/psmove/
