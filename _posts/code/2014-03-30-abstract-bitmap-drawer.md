---
layout: codepost
title:  Abstract Bitmap Drawer
category: code
feature-image: "/assets/img/20140330.jpg"
---
Ok, so, I’ve been on a quest for a while to create algorithms that can generate something pretty via code, with the caveat being that it has to be generated at random. Creating an algorithm that results in the same thing every time is great, and all, but what interests me is the border between randomness and intentional design that can lead to interesting results, and treading that border as closely as possible.

For this example, I created some functions that paint, and this process can be started and stopped whenever an interesting result is arrived at, and then saved. So it still requires a user to determine what is interesting, but it is a step in the direction of generated art.

If you follow the project link to the right, be aware. The size of the SWF is much larger than most screens to create a print-worthy document, so unless your screen res is pretty insane, you will likely have to use the browser command to zoom out (⌘ – on Chrome on the Mac, you’ll have to check for your specific browser) until you can see the control buttons in the lower right. Also, it starts with a white canvas, so it will look at first like nothing is happening.

Below is the ActionScript code for this example. If you paste this into any new project you can recreate this experiment (I was lazy on this one and didn’t develop any proper class structure since I was writing it off the cuff). This could stand some revision and cleanup in that respect, and the only reason I haven’t yet is because I want to move the whole thing over to HTML5/JavaScript to continue refining it there. Haven’t had time to do that yet. I will post those files as a git repo when I get to it.
