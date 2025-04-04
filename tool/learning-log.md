# Tool Learning Log

## Tool: Aframe

---

3/16/25:
* From the previous Monday I had explored what Mr. Mueller taught me to do in class. He said I should go to the A-frame website and press on docs. I should copy it into my IDE first to see how it works and then tinker with it. That is what I did, I changed the positions, the colors, and observed what numbers made up the shapes. Then I thought about how to associate it with <b>Movie Production</b>, and I found a solution. Since I spent a long time researching hardware, I can build a 3D model of a camera. Not the super techy ones I researched about, but to start off, I'd build a resemblance of one.
  *   Since tinkering of this week I have explored more of the page and eventually saw that they had a Slack and Github account to research more of their tool on <a href="https://github.com/aframevr/aframe/tree/master/docs/components" target="_blank">Visit A-Frame Components Docs</a>
  *   I also watched part of the video of where this guy used the inspector tool to put geometric shapes on top of each other. <a href="https://www.youtube.com/watch?v=UYT97ZHPvEY">Youtube Inspection Tool</a>

* I think the biggest challenge was to add the text on top of the camera. I just wanted to do it so people understand what it is because I know it's not the clearest 3D picture of one, but the more I tinker, the better I will get. I had trouble with getting it where I wanted to but I realized that I had to put "align" when I asked a friend. But I wasn't sure if it was going to work because "align" popped up as red which I thought was incorrect on my IDE but it turned out working fine. 

```html
<a-text value="Camera Model" position="0 3 -4" color="black" align="center" scale="2 2 2"></a-text>
        </a-scene>
```

At first for planning, I decided to split up a camera into different parts and comment it in my IDE so I wouldn't forget which parts I had to make out of those geometry shapes and I had to have a color wheel opened on tab to make sure I got the colors right.

* Overall, I also tried their little games on the website to see how A-frame is more like VR. And I think that can be perfect for my project if we can create movies inside VR using A-frame, because I also saw that they specilize in <b>animations</b> and have a <b>music</b> folder where you can learrn to add audios in the background. 

* Maybe the only question I have is whether or not are these 3D models interactable and how do I approach that and add that to my FP. But that's really all I did for my thinking, I've learned so much and will improve my camera or make another hardware from my list next time.







### 3/23/35:
I learned about many different types of lights that I can incorporate into my freedom project to add style or serve the purposes of my hardware devices as well.
<p> There are five differernt lights </p>

* Directional Light
<ul>

* shadows (high contrast)

* like sunlight
</ul>

* Point Light
<ul>

* one place light

* lightbulb effect
</ul>

*   Ambient Light
<ul>

* no shadows

* brightness everywhere
</ul>

* Spot Light
<ul>

* pointed triangle light (good for lights like stage)

* different sides of light and opacity
</ul>

* Hemisphere Light
<ul>

* shadows (low contrast)

* two different hues
</ul>

I watched this video for some inspiration on the differrent types of lighting and how to manage them: https://www.youtube.com/watch?v=7GEvyHcy-og.

A challenge that I had was deciphering the difference between spot and point lights, but the video explained them pretty well.

```html
<a-light type="spot" color="FF0000" position="-20 0 0" look-at="a-box"></a-light>

```


Basically, a spotlight is like a cone focused on one object or scene, while a point light is also focused on the same object but bounces off in all directions, illuminating the surrounding area.

Overall, I think the spotlight will work better for my project, which is why I inserted the code here so I can use it later for little details in my Freedom Project.

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->




<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->

