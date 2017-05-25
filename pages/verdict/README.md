[verdict-project_img]: /assets/images/projects/verdict-project.png
[verdict-joints_img]: /assets/images/projects/verdict-joints.png
[verdict-spine_img]: /assets/images/projects/verdict-spine.png
[verdict-prototype_gif]: /assets/images/projects/verdict-prototype.gif
[no]: /assets/images/projects/no.png
[yes]: /assets/images/projects/yes.png

[verdict-prototype]: https://nerdmanship.github.io/McGregor_prototype/
[verdict_animation]: https://nerdmanship.github.io/_verdict-module/dist/
[svg-link]: https://en.wikipedia.org/wiki/Scalable_Vector_Graphics
[gsap-link]: https://www.greensock.com

# App Promoting Website Header

(Jan 2017)

![Picture][verdict-project_img]

#### [Launch demo][verdict_animation]

## Summary

* Made to entertain and educate potential app users so they would get excited enough to download the app
* New animation techniques was developed to make fighting motion appear realistic
* *Some success stats coming soon*

---

## About the project

**Verdict MMA is the Fantasy Football for Ultimate Fighting**. Fans use the app to make essential fight predictions before real sports events and to score rounds in real-time during them. The results of scoring and predicting fights are compared to other players around the world, creating a global top list in which the greatest ultra fans are rewarded for their fluke and nerd-level knowledge.

The animation was made to promote the app by grabbing the attention of potential users at the very first second and to make them froth while learning what the app is about. Relevant and relatable content engage, so by letting superstars Nate Diaz and Conor McGregor beat the shit out of each other, we hoped to really excite every MMA fan that would visit the page. 

---

#### Animation challenges

As in all other projects, everything is [code based graphics][svg-link] animated with [javascript][gsap-link]. The characters are both made of graphic elements that are connected by the joints resembling a human skeleton. Setting up a character like this means that motion will seem realistic as long as it stays true to that skeleton structure. 

![][verdict-joints_img]
 
With the right setup, and with some animation principles in mind, just a few lines of code can create a pretty compelling look. Here's [an early prototype][verdict-prototype] that demonstrates that.

![][verdict-prototype_gif]

During my research I realised that hip rotation is super essential to create believable fighting motion, so I needed a way to make the 100% flat bodies appear to be rotating around the spine. To achieve this *faux 3D effect* I divided graphics in elements that in real life would be closer to and further away from the camera. Imagine a person with its left side towards you. The left shoulder is closer to you than the right one. By animating left and right shoulder in opposite directions you can create a fake sense of depth and make the character appear as it's rotating around its spine.

![][verdict-spine_img]

The visual result is a scene with depth. Instead of having characters that look like flat cutouts, they appear more life-like as silhouettes shot in backlight.

I learned a lot of valuable lessons and had many reusable insights doing this projects – both from a visual and code development perspective. I really look forward to future projects involving character design, anatomy and kinetics. The code I write will be smarter and more performant code, and the visual results will be greater.


---


## Tech spec*

| Category | Total weight | FPS Desktop | FPS Mobile | Responsive | All Browsers |
| :-------- | :-----: | :-----: | :-----: |  :-----: | :-----: |
| App promotion | 108 kB | 30-60 | 30-40 | ![][yes] | ![][yes] |


---



# ❤️ Let's be friends!

### Drop me a line at [johan@nerdmanship.com](mailto:johan@nerdmanship.com) or pick your favourite poison below:

* Get nerdy animation updates on the [Facebook Page](http://www.facebook.com/nerdmanship).
* I share things that impress me on [Twitter](http://www.twitter.com/stromqvist).
* I'm forced to degrade my projects on [Dribbble](http://www.dribbble.com/stromqvist).
* All my experiments end up at [Codepen](http://www.codepen.io/nerdmanship).
* I keep a friends list of emails too. [Sign up here](http://nerdmanship.us13.list-manage.com/subscribe/post?u=bed6727a7b59b995ae23ca252&id=706f47db11).

---

## License

The code is available under the [MIT license](LICENSE.txt).

---

#### *

|  | **What does the table mean?** |
| :-------- | :----- |
| **Category** | Distinguishing subdivision of all projects |
| **Total weight** | Total file size of minified and compressed project including all dependencies |
| **Fps** | Amount of frames rendered each second (max 60). An indicator on how well the code performs when tested on current version of the most common browsers. Most common **desktop** browser in North America is currently: [Chrome](http://gs.statcounter.com/browser-market-share/desktop/north-america/#monthly-201604-201704). Most common **mobile** browser in North America is currently: [Safari](http://gs.statcounter.com/browser-market-share/mobile/north-america/#monthly-201604-201704) |
| **Responsive** | Animated/interactive content responds and adapts to the screen size of user's device |
| **All Browser** | Project works on all currently supported versions of Chrome, Firefox, Safari, MS Internet Explorer and MS Edge |

