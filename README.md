### Hi there, I'm Luca Dillenburg <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"> <a href="https://twitter.com/intent/follow?screen_name=lucadillenburg"><img align="right" src="https://img.shields.io/twitter/follow/lucadillenburg?style=social&logo=twitter" alt="follow on Twitter"></a> <a href="https://github.com/LucaDillenburg/"><img align="right" src="https://img.shields.io/github/followers/lucadillenburg?style=social&logo=github" alt="follow on Github"></a>

## I'm a Full-Stack developer and Entrepreneur!

- 🥅 2021 Goals:
  - Create the best delivery app to eat vegan or vegetarian food
  - [x] Learn to skydive
- 🌱 I’m currently learning Design, Management and Entrepreneurship
- 👯 I’m looking to collaborate with other entrepreneurs and fullstack devs
- 💬 Ask me about entrepreneurship, Flutter, Firebase, and GoLang
- ⚡ Fun facts: I believe in Christ, I am vegetarian and I love extreme sports

---

## :fireworks: Works I'm most proud of

<details>
  <summary>:green_heart: <b><i>Legumo</b></i>: the delivery app to eat vegan or vegetarian food </summary>
  
  - Instagram: [@legumo.app](https://instagram.com/legumo.app)
  - Site: [https://legumo.com.br](https://legumo.com.br)
</details>

<details>
  <summary>🎨 <b><i>Colorblind Toolset</b></i> </summary>

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
  <summary>:gun: <b><i>2D Engine for Fire Games</b></i>: developed from scratch and supports many geometric shapes</summary>

## Summary
Engine para for 2D top-down gun games. It supports colisions between any polygon without curved sides. It also has follower objects (i.e.: guided missiles) and super powers such as slow down time and freeze enemies.

***Check out the [repo](https://github.com/LucaDillenburg/Engine-2D-Jogo-de-Tiro/)***

## Example of game using the engine
<img alt="2D Engine for Fire Games" width="70%" src="https://raw.githubusercontent.com/LucaDillenburg/Engine-2D-Jogo-de-Tiro/master/exemplo-jogo.gif"/>

</details>

<details>
  <summary>:computer: <b><i>Open Machine</b></i> (WIP) - an Open-Source computer</summary>

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

---

### 📕 Articles
- *Latest Article*

  <a href="https://github-readme-medium-recent-article.vercel.app/medium/@luca.assumpcao.dillenburg/0" target="_blank"><img src="https://github-readme-medium-recent-article.vercel.app/medium/@luca.assumpcao.dillenburg/0" alt="Recent Article 0"></a>

- *Check out all articles [here](https://medium.com/@luca.assumpcao.dillenburg)*

---

### 🧭 Preffered Languages and Tools

<img align="left" alt="Flutter" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/flutter/flutter.png" />
<img align="left" alt="GoLang" width="26px" src="https://raw.githubusercontent.com/LucaDillenburg/LucaDillenburg/master/media/golang.png" />
<img align="left" alt="Spark" width="26px" src="https://raw.githubusercontent.com/LucaDillenburg/LucaDillenburg/master/media/spark.png" />
<img align="left" alt="Firebase" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/firebase/firebase.png" />
<img align="left" alt="Figma" width="26px" src="https://raw.githubusercontent.com/LucaDillenburg/LucaDillenburg/master/media/figma.png" />

<!-- <i>Also some experience with: MySQL, MongoDB, Nodejs and Nextjs.</i> -->

<br />

---

### 🗣️ Connect with me

<a target="_blank" href="https://twitter.com/lucadillenburg">
  <img align="left" alt="@lucadilleburg | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>

<a target="_blank" href="https://linkedin.com/in/luca-dillenburg">
  <img align="left" alt="Luca Dillenburg | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
</a>

<a target="_blank" href="https://instagram.com/LucaDillenburg">
  <img align="left" alt="Luca Dillenburg | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />
</a>

<a target="_blank" href="mailto: luca.assumpcao.dillenburg@gmail.com">
  <img align="left" alt="luca.assumpcao.dillenburg@gmail.com" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/gmail.svg" />
</a>

<br/>
<br/>

---

<details>
  <summary>⏱️ Weekly Time Spent</summary>

  ### This week I spent my time on:
  <!--START_SECTION:waka-->

```text
From: 09 May 2022 - To: 16 May 2022

Dart         3 hrs 46 mins   █████████░░░░░░░░░░░░░░░░   36.48 %
TeX          3 hrs 11 mins   ███████▓░░░░░░░░░░░░░░░░░   30.90 %
TypeScript   1 hr 1 min      ██▒░░░░░░░░░░░░░░░░░░░░░░   09.99 %
Markdown     43 mins         █▓░░░░░░░░░░░░░░░░░░░░░░░   07.07 %
Other        43 mins         █▓░░░░░░░░░░░░░░░░░░░░░░░   06.94 %
```

<!--END_SECTION:waka-->
  <br/>
</details>

<details>
  <summary>:zap: Github Stats</summary>

  <img align="left" alt="LucaDillenburg's Github Stats" src="https://github-readme-stats.vercel.app/api?username=LucaDillenburg&show_icons=true&hide_border=true&count_private=true" />

  <br/>
</details>
