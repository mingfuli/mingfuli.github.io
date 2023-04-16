---
title: "Grandma Green"
excerpt: "<img src='/images/ggbanner_1.jpg'><br/><i>Gameplay AI Engineer / Unity / Coming to Mobile<i>"
collection: portfolio
---

<!-- <body>
    <center>
    <blockquote class="twitter-tweet"><p lang="en" dir="ltr">Alpha update for Grandma Green - a cozy gardening sim for mobile! Coming Spring 2023! 🌷❤️<a href="https://twitter.com/hashtag/grandmagreen?src=hash&amp;ref_src=twsrc%5Etfw">#grandmagreen</a> | <a href="https://twitter.com/hashtag/indiedev?src=hash&amp;ref_src=twsrc%5Etfw">#indiedev</a> | <a href="https://twitter.com/hashtag/cozydev?src=hash&amp;ref_src=twsrc%5Etfw">#cozydev</a> | <a href="https://twitter.com/hashtag/indiegame?src=hash&amp;ref_src=twsrc%5Etfw">#indiegame</a> | <a href="https://twitter.com/hashtag/cozygame?src=hash&amp;ref_src=twsrc%5Etfw">#cozygame</a> | <a href="https://twitter.com/hashtag/gardeningsim?src=hash&amp;ref_src=twsrc%5Etfw">#gardeningsim</a> | <a href="https://twitter.com/hashtag/gamedev?src=hash&amp;ref_src=twsrc%5Etfw">#gamedev</a> | <a href="https://twitter.com/hashtag/IndieGameDev?src=hash&amp;ref_src=twsrc%5Etfw">#IndieGameDev</a> | <a href="https://twitter.com/hashtag/2dart?src=hash&amp;ref_src=twsrc%5Etfw">#2dart</a> | <a href="https://twitter.com/hashtag/uscgames?src=hash&amp;ref_src=twsrc%5Etfw">#uscgames</a> <a href="https://t.co/u5cEkck9Dx">pic.twitter.com/u5cEkck9Dx</a></p>&mdash; 💚 Grandma Green 💚 (@grannygreengame) <a href="https://twitter.com/grannygreengame/status/1603126430333865984?ref_src=twsrc%5Etfw">December 14, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    </center>
</body> -->
<iframe width="443" height="788" src="https://www.youtube.com/embed/FggDHHqdLIU" title="Upcoming FREE cozy gardening game for iOS and Android" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Grandma Green is a 2D simulation game developed by a team of ~20 USC students. Currently, the game is in the beta stage. I am the Gameplay AI Engineer in the team, where I mainly worked on the AI system of our plant friends. I also supported the development of our player character control and NPC interactions.  

### Tech Stack
Unity, C#, Behavior Tree, State Machine

### Development Time
Sep 2022 - Present

### Creating Our Plant Friends
<iframe width="480" height="270"
src="https://www.youtube.com/embed/EfACmy3D3ps">
</iframe>

* The Golem system which includes golems spawning, evolution, and emotion handling. Golems start out as a Baby, and evolve into a Grown-up when they max out their happiness meter. Players can assign task to a Grown-up can golems to help building their garden.  
* I developed and provided the emotion and exressions handling APIs to other engineers in the team. The APIs follows Publish–subscribe pattern. My engineering peers, who worked for UI and dialogue, can easily update a golem's emotion and expression in a decoupling and elegant manner.

### Driven by Behavior Tree
<center><img src='/images/npbehave_window.png'><br/></center>

* Implemented Golems' interaction and behaviors using behavior tree
* Incorporated and maintained AI tool and Event Manager in our project
 

### Building Our Character Pipeline
Working closely with our artists, I help build our 2d character pipeline. Our game has a variety of lovely characters including Grandma, Shopkeepers, and Golems. responsible for managing the entire pipeline or for overseeing specific stages of the process. from import, rigging, animation all the way to scripting.
