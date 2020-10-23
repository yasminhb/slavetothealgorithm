# week 10...making good progress!!!

Last week I had drawn up all of my backgrounds and animations. This weeks challenge was to put them all together and combine the facial tracking code (my script.js and my sketch.js). This was honestly my biggest challenge as I really had NO IDEA how to do it. 

#### This is what the animations and backgrounds look like when put together:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2010/ezgif-4-751ea15dd6cf.gif>

### UPON FURTHER INSPECTION I DISCOVERED SOMETHING...

I didn't realise there was an entirely new EMOTION that was apart of the facial tracking code that I completely OVERLOOKED!

I have NO IDEA how I managed to overlook the fact that the facial tracking code had included 'fearful' as an emotion. 

Perhaps because this is one of the harder emotions to recreate? I had never seen this emotion pop up on my screen when I was testing the emotion detection.

I googled 'fearful expression' and this is what came up:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2010/fearful-face.jpg>

Image via: https://gettingstronger.org/2012/12/conquer-your-fears/fearful-face/

So I gave it a go and...

IT WORKED?? Apparently this is what you look like when you're scared and I've almost mastered this expression.

#### TIP: *The hands covering the chin is the key.*

What does this mean? It means I had to quickly draw a new background and complimentary animations. 
Thankfully I had a quick sketch from a few weeks back for what I would have done if I had 'fearful' as one of the emotions and ran with that. 

#### This is what I came up with:

*The background:*

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2010/fearsky.jpg>

I've found that night time is the most scary state of any enviroment, because people aren't afraid of the dark, they're afraid of the unknown. 

*Added animation:*

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2010/r20.png>

I thought adding a rainbow would eliminate the scary sense that this background had, it also contrasts really nicely and adds a nice pop of colour.

*For the flowers...*

I decided to use a similar flower animation that I used for the sad emotion, but reverse it. 

This way it looks like a flower is *hiding*, most likely from being scared. 

### WORKING ON THE CODE

I knew combining the two .js files would be super tricky, so I looked a little closer at the code.

I managed to create values like this:

*INSERT IMAGE*

When I looked at the console I realised that the expressions data came out as numbers, with the highest number being the emotion that was detected and displayed on the screen. I then realised that I had to somehow tell the code to take the biggest number from the results and use the biggest number as an input for the next function (rather than taking all data and displaying multiple unwanted images on screen). Karen suggested I look into the sort() function. The sort() function kind of confused me but I realised it was basically just creating an array[] of objects and so I did some further research. 

#### By creating values and researching arrays and objects, I managed to come up with this in the console:

*INSERT IMAGE*

Minh and I got down to business and starting researching 'if' and 'else' functions. 
We spent HOURS trying to get our 'if' and 'else' functions to work but it just wouldn't! We also didn't know why it wasn't working as we had seemingly done everything right. 

#### This is what we came up with:

*INSERT IMAGE*

As a test, I tried to make the word 'happy' appear in the console, otherwise it would say 'not happy'. 

I managed to get the word 'happy' appear in the console, but it would appear for every emotion and the 'not happy' never appeared. 

We were both honestly SO confused and decided to make a meeting with Karen. After about 5 seconds Karen noticed I was missing a double equals sign (I had '=' instead of '=='). I added it and it WORKED. I was so happy but I felt SO DUMB AT THE SAME TIME HAHA. 

Nevertheless, this was a...

### BREAKTHROUGH

#### I had another go with all of the images this time and this is what I got:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2010/ezgif-7-a1aac17be949.gif>

I successfully managed to connect the two codes!!

I was trying to put my facial tracking code into my animation code, but it kept breaking. It finally worked when I put the animnations into the facial tracking code and did it the other way around. 

My next big challenge was hiding the camera so the viewer can't see their face and focuses on the screen. The animations were also on the side of the screen and you had to scroll over to access it, which was actually quite annoying and made the sketch fairly confusing. The two canvas' were actually kind of tricky to navigate, and I couldn't quite figure out where the canvas for the video was in the code. I finally found that the perimeters were declared in the index.html rather than the .js files. 

I tried to hide the camera view entirely but it broke the code as it needs to recognise the camera to create data. I decided to just make the camera view so small that it basically seems invisible and that seemed to work and I had fixed the canvas issue.

Karen did mention that she wanted the sketches to be windowWidth and windowHeight rather than a fixed size, this way it would be viewed on all screens and devices. I had experimented with resizing animations a couple weeks ago but found that I couldn't resize animations without breaking them. She then suggested that I use the scale() function. 

#### After trying the scale() function this is what happened:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2010/ezgif-7-d4eb679c64a0.gif>

As my facial expression was contiously changing and the screen was fluxuating so often, everytime it would draw a new screen (which was every few seconds) it would scale the entire screen smaller (including other screens that were different emotions). I'm not sure I'll be able to use windowWidth, and windowHeight as I've tried a few different things but it doesn't seem too animation friendly. I'll definitely try to research this topic a little bit more. 

### Adding Sound

I honestly didn't think I would be able get to this part as I really didn't think I would be able to combine the facial tracking code with the animations at all. 
I downloaded a few different sounds (mostly nature sounds like thunder and rain).  

#### A common mistake I made with the sounds was forgetting to folder it was in

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2010/Screen%20Shot%202020-10-08%20at%205.06.56%20pm.png>

I made this mistake a lot with the animations and wasn't sure why I didn't remember to do it this time, but really confused as to why none of the sounds were loading. At first I thought it was the file size until my friend pointed out my mistake.

Karen mentioned it was probably best to use a mousePressed() function with sound, as then the viewers have the option to use sound or not (as it can be annoying especially if you don't know the source or can't mute it). 

I'm currently experimenting with sound and managed to get the sounds to work, but only when you click on the screen of a particular emotion (meaning you have to continously click the screen perfectly timed) which is fairly tiring. The sound also carries on when you switch emotions, so I'll have to research p5.js sound a little bit more. 

#### This is my current code for the sound portion:

*INSERT IMAGE*







