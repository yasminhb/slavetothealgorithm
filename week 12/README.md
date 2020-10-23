# week 12... FINAL PRESENTATION AHHHHHH!!!

Let me give you a run through of what I presented...

#### Here is the working link:

yasminhb.github.io

### The Code

#### Facial Tracking

A quick run down and summary of my code (I cleaned it up a LOT):

The facial tracking and emotion detection code was entirely created by Web Dev Simplified via:
https://github.com/WebDevSimplified/Face-Detection-JavaScript

It uses the face.api library, and was slightly remixed by me in order to fit my particular idea.

#### Emotion Detection

Emotion detection is included as part of the code by Web Dev Simplified (ADD NAME OF GUY), however, I created an array using objects and values in order to gather information and use it as an input.

This can be seen here:
<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2012/Screen%20Shot%202020-10-23%20at%208.12.50%20pm.png>

Here I was able to define all of the emotions as numbers, meaning I could take the largest data set and connect it with my next function.

This can also be seen in my console (screen shot taken from a few weeks ago and is no longer available in the current console):

*INSERT IMAGE*

If no face is detected, this will show in the console (updated):

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2012/Screen%20Shot%202020-10-23%20at%208.19.40%20pm.png>

#### Background Images

As I hand drew all of the images, this part of the code was actually quite easy. I loaded all of the images in and then used the if{} function in order to be selective with what is shown and drawn to the screen (depending on the emotion shown by the user).

This is what loading the background images with the animations looks like in the code:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2012/Screen%20Shot%202020-10-23%20at%208.21.21%20pm.png>

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2012/Screen%20Shot%202020-10-23%20at%208.21.37%20pm.png>

#### Animations

In order to create the animations, I used the p5.play library. I was able to create the animations by ordering images (frames of my drawn animation) and using the animation() function. 

Similar to the background images, I used the if{} and else{} function in order to connect these animations with the users emotion (as well as the background).

You can see how I loaded and created the animations in the code below:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2012/Screen%20Shot%202020-10-23%20at%208.21.15%20pm.png>

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2012/Screen%20Shot%202020-10-23%20at%208.22.38%20pm.png>

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2012/Screen%20Shot%202020-10-23%20at%208.22.58%20pm.png>

### Sound

The sound is an optional function and works by using the mousePressed() function. Similar to the animations, if the user is showing a certain facial expression the corresponding sound will trigger (on mousePressed). The sound can also be stopped prematurely by switching emotions.

This is what the code looks like:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2012/Screen%20Shot%202020-10-23%20at%208.22.00%20pm.png>


### The Working Sketch

By combining all of the functions and inputs from above, I managed to create a working sketch: *the garden of pathetic fallacy!*

Once all of these functions are connected, the sketch works sort of like this:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2012/YHB%20Project%20Gif.gif>

For reference, I have included my photobooth application on the side so you can see my face changing (and how the sketch works). 

#### *So what does the user experience exactly?*

The sketch first loads the landing page which gives them instructions and briefly explains the sketch, as well as how it works.

After clicking *ENTER* the user then enters the sketch and can interact with the garden by changing their facial expression. 

I've found it's really fun to try and find all seven of the garden states (as some emotions are harder to imitate than others). 

It's definitely a lot of fun and feel like it would especially be fun for children to play around with. 

Perhaps this is something I could expand upon?


