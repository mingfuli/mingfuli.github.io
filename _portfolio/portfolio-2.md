---
title: "Grandma Green"
excerpt: "<img src='/images/ggbanner_1.jpg'><br/><i>Gameplay AI Engineer / Unity / Coming to Mobile<i>"
collection: portfolio
---

<body>
    <center>
    <blockquote class="twitter-tweet"><p lang="en" dir="ltr">Alpha update for Grandma Green - a cozy gardening sim for mobile! Coming Spring 2023! 🌷❤️<a href="https://twitter.com/hashtag/grandmagreen?src=hash&amp;ref_src=twsrc%5Etfw">#grandmagreen</a> | <a href="https://twitter.com/hashtag/indiedev?src=hash&amp;ref_src=twsrc%5Etfw">#indiedev</a> | <a href="https://twitter.com/hashtag/cozydev?src=hash&amp;ref_src=twsrc%5Etfw">#cozydev</a> | <a href="https://twitter.com/hashtag/indiegame?src=hash&amp;ref_src=twsrc%5Etfw">#indiegame</a> | <a href="https://twitter.com/hashtag/cozygame?src=hash&amp;ref_src=twsrc%5Etfw">#cozygame</a> | <a href="https://twitter.com/hashtag/gardeningsim?src=hash&amp;ref_src=twsrc%5Etfw">#gardeningsim</a> | <a href="https://twitter.com/hashtag/gamedev?src=hash&amp;ref_src=twsrc%5Etfw">#gamedev</a> | <a href="https://twitter.com/hashtag/IndieGameDev?src=hash&amp;ref_src=twsrc%5Etfw">#IndieGameDev</a> | <a href="https://twitter.com/hashtag/2dart?src=hash&amp;ref_src=twsrc%5Etfw">#2dart</a> | <a href="https://twitter.com/hashtag/uscgames?src=hash&amp;ref_src=twsrc%5Etfw">#uscgames</a> <a href="https://t.co/u5cEkck9Dx">pic.twitter.com/u5cEkck9Dx</a></p>&mdash; 💚 Grandma Green 💚 (@grannygreengame) <a href="https://twitter.com/grannygreengame/status/1603126430333865984?ref_src=twsrc%5Etfw">December 14, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    </center>
</body>

Grandma Green is a 2D simulation game developed by a team of ~20 USC students. Currently, the game is in the beta stage. I am the Gameplay AI Engineer in the team, where I mainly worked on the AI system of our plant friends "golems". I also supported the development of our player character control and NPC interactions. Besides gameplay features, I am also responsible for maintaining some dev tools in our project, including AI tools Event Manager in our project. 

### Tech Stack
Unity, C#, Behavior Tree, State Machine

### Development Time
Sep 2022 - Present

### Creating Our Plant Friends
<iframe width="480" height="270"
src="https://www.youtube.com/embed/EfACmy3D3ps" &autoplay=1>
</iframe>

* The Golem system includes golems spawning, evolution, emotion handling and task action. Golems start out as a Baby, and evolve into a Grown-up when they max out their happiness meter. Players can assign task to a Grown-up can golems to help building their garden.  
* I developed and provided the emotion and exressions handling APIs to other engineers in the team. The APIs follows Publish–subscribe pattern. My engineering peers, who worked for UI and dialogue, can easily update a golem's emotion and expression in a decoupling manner.

### Building Our Character Production Pipeline
<img src = '/images/CHApipeline.png'><br/>
* Working closely with our artists and other engineers, I am responsible for building our characters production pipeline. Our game has a variety of lovely characters including Grandma, Shopkeepers, and Golems. My role involves coordinating with team members across various stages of the pipeline, so that everyone can work in parallel and deliver content faster.

### Golems Interaction and Behaviors
<iframe width="480" height="270"
src="https://www.youtube.com/embed/wUzI3ZM0hH4">
</iframe>
* I implemented Golems' interaction and behaviors using Behavior Tree. Players can tap to talk to a golem or drag to move a golem. 
* To achieve golem watering action, I created a CrowdController to communicate with Garden Controller to get plants which need to be watered. CrowdController will schedule and assign tasks to each single valid golem. 