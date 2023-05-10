<h1 style="text-align: center">Hi there, I'm Luca Dillenburg <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"/></h1>

<img src="https://raw.githubusercontent.com/LucaDillenburg/LucaDillenburg/master/media/Banner.png" alt="Design & Development for startups">

## About Me
I'm an entrepreneur and fullstack developer!
- My goal in 2023 is to build a susteinable development team for startups and small businesses
- I’m currently learning design and entrepreneurship
- I’m looking to collaborate with entrepreneurs and fullstack devs.
- Fun fact: I am a skydiver on the weekends

<br/>

## Works I'm most proud of

<details>
  <summary><b>Legumo</b>: the delivery app to eat vegan or vegetarian food </summary>
  
  - Instagram: [@legumo.app](https://instagram.com/legumo.app)
  - Site: [https://legumo.com.br](https://legumo.com.br)
  - Download: [Play Store](https://play.google.com/store/apps/details?id=br.com.legumo) e [App Store](https://apps.apple.com/br/app/legumo/id1589305379?l=en)
</details>

<details>
  <summary><b>Colorblind Toolset</b>: android app for colorblinds </summary>

## Summary
*Colorblind Toolset* is a mobile application with several tools that target the most common colorblind problems in their daily lives.
It was developed for all color blindness types.

***[ ⚠️ Disclaimer: This app is not open-source. ]***

## Tools
  <details>
    <summary>1. <b><i>Color blind friendly maps</b></i> generated from other maps </summary>

  #### The Problem
  Several people have to read maps regularly, some of them at school, at university or at work. Unfortunately, most maps can only be understood by differentiating colors, making this task very difficult for color-blind people.

  #### The Solution
  The algorithm groups the pixels by color and turns each group into a different pattern so that the map can be read even without any color.

  *Check out a demonstration below:*
  
  <img alt="Colorblind friendly map generation" src="https://raw.githubusercontent.com/LucaDillenburg/LucaDillenburg/master/media/map-colorblind-toolset.gif"/>

  </details>

  <details>
    <summary>2. <b><i>Display color names</b></i></summary>
    
  #### The Problem
  There are countless reasons why a colorblind would want to know the color of something.<br/>
  They may want to know if a banana is ripe, or the color of a shirt when choosing their clothes. In these situations, there's nothing to do but to ask for help. 
  
  #### The Solution
  This tool is here to help them to it for their own. It displays the names of the colors inside the square at the center of the screen. Also, the square size is configurable.

  #### Demonstration
  *Check out a demonstration below:*
  <img alt="Display color name" src="https://raw.githubusercontent.com/LucaDillenburg/LucaDillenburg/master/media/colorname.jpeg"/>

  </details>
  
  <details>
    <summary>3. <b><i>Super color differentiation</b></i> to improve interpretability</summary>
    
  #### The Problem
  Two very different colors can look the same in the eyes of people with color blindness. This may keep people with this vision deficiency from being able to read something for example.
  
  #### The Solution
  This tool is a color filter that increases the color differentiation. 

  #### Solution Algorithm Explained
  The algorithm changes the color of every pixel based on its Hue (saturation and lightness are not considered) following the logic below:
  - The hue color wheel is divided in two.
  - One of them will have shades of {COLOR 1} and the other will have shades of {COLOR 2}.
  - Both sides will begin together with white and darken {COLOR 1} and {COLOR 2} until start in of the colors will go from 
  - {COLOR 1} and {COLOR 2} must be two colors that the colorblind can easily differentiate. These colors should be changed depending on the type of color blindness.
  - The result is:
  
  Original | With filter
  --- | ---
  <img alt="Color hue" height="200px" src="https://raw.githubusercontent.com/LucaDillenburg/LucaDillenburg/master/media/colorhue-nofilter.jpg"/> | <img alt="Color hue with filter" height="200px" src="https://raw.githubusercontent.com/LucaDillenburg/LucaDillenburg/master/media/colorhue-filter.jpg"/>
  
  #### Demonstration
  Check out how people with deuteranopia and protanopia (two kinds of colorblindness) see the colorblindness test and what they see with the filter. Since the two colors were choosen so that the colorblind can easily differentiate them, what you see on the right column is very close to what the colorblind will see.
  
  Original  | With filter
  --- | ---
  <img alt="Colorblind test without any filter" height="250px" src="https://raw.githubusercontent.com/LucaDillenburg/LucaDillenburg/master/media/colorblind-test-comparisson.png"/> | <img alt="Colorblind test with our filter" height="250px" src="https://raw.githubusercontent.com/LucaDillenburg/LucaDillenburg/master/media/colorblindness-test-filter.jpg"/>

  </details>

## Developers
- This project was developed by: [me](https://github.com/LucaDillenburg), [Eduardo Porto](https://github.com/edusporto) and [Fábio Faúndes](https://github.com/fabiofaundes);
- Fun fact: Eduardo e Fábio are colorblind.

</details>

<details>
  <summary><b>2D Engine for Fire Games</b>: developed from scratch and supports many geometric shapes</summary>

## Summary
Engine para for 2D top-down gun games. It supports colisions between any polygon without curved sides. It also has follower objects (i.e.: guided missiles) and super powers such as slow down time and freeze enemies.

***Check out the [repo](https://github.com/LucaDillenburg/Engine-2D-Jogo-de-Tiro/)***

## Example of game using the engine
<img alt="2D Engine for Fire Games" width="70%" src="https://raw.githubusercontent.com/LucaDillenburg/Engine-2D-Jogo-de-Tiro/master/exemplo-jogo.gif"/>

</details>

<details>
  <summary><b>Open Machine</b>: a simple open-source computer</summary>

<br/>

## 💡 The Idea

The idea came from an [article](https://medium.com/@luca.assumpcao.dillenburg/programming-tips-from-a-not-yet-experienced-programmer-754623ce28ae) I wrote about some tips for developers:

> And a message for those (myself included) that still want to build apps entirely from scratch because "That's the only way it will feel my doing only":
> 
> There's nothing wrong with building it from scratch. On the contrary, you can learn so much more when doing so. However, don't fool yourself into thinking that you built it entirely yourself. No program is created by just one person. If you want to achieve this, go ahead and start picking up some stones to build your computer first, then you can create your programming language and only then, your program.

I was obviously not encouraging people in any way to do that, but a few weeks later I asked myself: "What if I do just that? Could I actually do it?".

[ ⚠️ **Disclaimer**: Of course, I am doing some research and using knowledge developed by many people over many years of study. So I'm still not building it entirely on my own. In fact, I don't think that's even an option anymore since everybody has some knowledge about computers today. ]

Anyway, with that out of the way, this is when the everything started: a small doubt in my head was fuel enough to face the challenge.

## Summary

The goal is to to design and build a computer from scratch. I will only use logical gates to build the circuit and GoLang to build the compiler and assembler for your computer.

I also want to understand how a computer works behind the curtains and maybe do some things my way.

## Components
  - Circuit
  - Machine Language Assembler
  - High-Level Language Compiler

## Learn more
Click [here](https://github.com/Open-Machine/Organization-README) to learn more.

</details>

<details>
  <summary><b>Article</b>: Programming tips from a not yet experienced programmer</summary>
<a href="https://medium.com/@luca.assumpcao.dillenburg/programming-tips-from-a-not-yet-experienced-programmer-754623ce28ae" target="_blank"><img src="https://medium.com/@luca.assumpcao.dillenburg/programming-tips-from-a-not-yet-experienced-programmer-754623ce28ae" alt="Programming tips from a not yet experienced programmer"></a>
</details>

<br/>

### Preffered Languages and Tools

<img align="left" alt="Flutter" width="26px" src="./icons/flutter.svg" />
<img align="left" alt="Flutter" width="26px" src="./icons/typescript.svg" />
<img align="left" alt="GoLang" width="26px" src="./icons/go.svg" />
<img align="left" alt="Firebase" width="26px" src="./icons/firebase.svg" />
<img align="left" alt="Figma" width="26px" src="./icons/figma.svg" />

<!-- <i>Also some experience with: MySQL, MongoDB, Nodejs and Nextjs.</i> -->

<br />
<br/>

### Connect with me

<a target="_blank" href="https://api.whatsapp.com/send?phone=5519991298440">
  <img align="left" alt="Luca Dillenburg | Whatsapp" width="22px" src="./icons/whatsapp.svg" />
</a>

<a target="_blank" href="https://linkedin.com/in/luca-dillenburg">
  <img align="left" alt="Luca Dillenburg | LinkedIn" width="22px" src="./icons/linkedin.svg" />
</a>

<a target="_blank" href="https://twitter.com/lucadillenburg">
  <img align="left" alt="@lucadilleburg | Twitter" width="22px" src="./icons/twitter.svg" />
</a>

<a target="_blank" href="mailto: luca.assumpcao.dillenburg@gmail.com">
  <img align="left" alt="luca.assumpcao.dillenburg@gmail.com" width="22px" src="./icons/gmail.svg" />
</a>
