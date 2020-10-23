# week 11... almost there!

Last week I finally managed to get the backgrounds linked with the facial tracking! A breakthrough!

This week I focused on getting all of the animations loaded in as well. I know from previous experience that you can't use the resize function on animations (otherwise it breaks the animation) so I tried using the scale() function, and also had trouble with that.

I managed to talk to Minh and Karen and got some advice on how I could use the scale() function in my sketch using something called push() and pop(). 

I had a go using this but couldn't get it to work :(

After countless attempts and research, Karen mentioned that it would be okay to present if it wasn't resized (it was just ideal to resize it to the window screen).

I managed to get something that sort of worked okay, however it was EXTREMELY hard to sync the position and size of the animations with the background and changing window screen. Ideally, I would want this project to be windowWidth and windowHeight so it could be viewed on all devices (including mobile phones).

I'll continue my research, but I'm not sure I'll be able to work it out by next week (finally presentation/class exhibition). 

#### This is what the interaction looks like (unscaled) with the backgrounds and animations together:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2011/ezgif-4-0422719609bf.gif>

### Creating a landing page

After I finally uploaded the sketch to a working github link and sent it to my friend (without explaining what the project was or what he was supposed to do) I realised that I need to include some sort of user instruction or infographic at the beginning to make things more clear. He noticed that the camera turned on, but wasn't aware of what the camera function was needed for, and thus felt really paranoid about someone watching him. My intention is definitely not to make people feel paranoid so it's important I explain what's going on to the user. 

#### This is what I have for the landing page:

<img src=https://github.com/yasminhb/slavetothealgorithm/blob/master/week%2011/landingpage.jpg>

I also decided to change the sound function of my sketch slightly. The emotions and animations fluctuate so often that it's difficult to continuously press the mouse each time. This may also get fairly tedius to a user, causing them to abandon this interaction altogether.  

I have still included a mousePressed() function as I think it's really important for sound to be an optional interaction for the user. 

Instead, as there was no pause or stop button, if users press down on a sound it will only play once (roughly ten seconds) and will cease immediately if the emotion changes. Previously, the sound would continue to play even if the emotion had changed. This way, the user can also easily choose to stop the sound by switching emotions. I decided not to loop the sound as I felt it was really annoying. The emotion usually changes every few seconds, so I felt looping it was also fairly unncessary. 

