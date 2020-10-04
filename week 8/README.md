# week 8...research research research

Karen suggested I explore the use of p5.play and sprites in order to create my animated garden.

I had no idea what it was and thought she was talking about the soft drink at first, so I decided to look into it.

Sprites are commonly used for video game animations, and are commonly used for characters in particular.

#### Here is an example of sprites frames:

Image Credit: https://godotengine.org/qa/19004/create-sprite-animation-from-single-image
<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%208/spritesheet-demo.png>

I came across a block based visual programming language called 'Scratch', which uses sprite characters in order to create interactive animations.

#### I had a go at creating another mockup, here is what it looked like:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%208/ezgif-3-a2492672e79c.gif>

Obviously I couldn't include the face tracking/emotion tracking portion of my idea but this was a good introduction to sprite characters and how it can be used for animation. 

My only concern is that the animation might not be that smooth if I do it this way. I think I need to look into how to animate on p5.play smoothly.

#### This is an example of what the 'code' blocks looked like:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%208/Screen%20Shot%202020-09-22%20at%202.15.00%20pm.png>


#### I managed to find a few sketches that showed a smooth background transition (although only one is done using javascript)!!

#### Here's an example of the one that uses processing:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%208/ezgif-3-8e2efd519b13.gif>

You can find the sketch here: https://www.openprocessing.org/sketch/945135

Here is the other sketch that is similar but uses javascript: https://www.openprocessing.org/sketch/526305

### Working on Visuals

After looking at my pseudocode, I decided to also try making some sketches for what the actual visuals could be.

It's better than I plan these out before so that the backgrounds and flower animations don't seem so 'random'.

#### Here are a few sketches I made for the visuals:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%208/Screen%20Shot%202020-10-04%20at%2011.38.37%20pm.png>

### Successful Face Tracking & Emotion Detection!!!

After WEEKS of trying to find a code/sketch that ACTUALLY worked for facial tracking and emotion detecting, I finally got one of the codes to work!!

To be honest, I was starting to get immensely stressed because this was the first function in my pseudocode, and my entire project depended on this function working. I had spent hours and hours trying to get various codes to work and I was starting to lose hope.

After downloading an application called Visual Studio Code, and using my terminal (which was super tricky but made me feel really cool) I managed to find a code that successfully detected emotions accurately. Only two of the sketches I found worked (one was in processing so I couldn't use it) but it failed to accurately detect my facial expressions (it said I was angry when I was smiling). 

#### Here is me trying out this new code:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%208/ezgif-7-b74536f28818.gif>

Facial Detection Code by WebDevSimplified
Via: https://www.youtube.com/watch?v=CVClHLwv-4I

As you can see, the facial tracking isn't completely accurate??

HOWEVER,

The emotion is detected correctly!! That's the most important part as that's the data I'll use to input into the other functions. 
Especially since the user won't be able to see their face anyway!

### Next Steps

Now I just have to figure out how to actually animate the garden in javascript. I also need to figure out how to import and animate the sprites.
This code that I used also only has 6 emotions, so I'll need to narrow done my pseudocode a little bit. 





