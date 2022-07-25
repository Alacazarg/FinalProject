# FinalProject
Final Project for Nvidia ID Tech Camp Course

  My project tackles the problem of blindness. It may look like just a regular image recognition A.I., but it can actually help save lives and prevent injuries. What my
A.I. can do is it finds all objects near by and through a speaker, will output what object is nearby, and when an object is nearby. Now, this can save lives for many reasons.
The first way it could help save lives is that if you were blind, you obviously cannot see a plain out screen tell you that there is an object nearby, but if it outputted
the results through sound, you would be able to hear it and stop walking into it. My device would also be able to help you for another reason. For instance, imagine you were
blind and you were using another program that just tells you if an object was spotted, you might thing nothing of it and might actually run into a dog and might injure the
dog and yourself, hurting two lives. Now, my program tells you what it is infront of you as well, so you would know a dog was right there. My program does have flaws, I 
cannot deny that, however I think my program is good for a 13 year old who really only had 5 days to work on this because I went on vacation. Also, even though my 
program sometimes guesses the object wrong, it is not because of the program itself, but because of the capabilities of the dataset and the jetson nano itself, 
the jetson nano 2gb simply does not have the power for more than 100 objects in a dataset, in my opinion. Now enough of the pros and cons of my device. Let me tell you
how it works. It works by using opencv  to constantly take a picture and display it onto the screen, making an illusion of live video. It will then take that image and 
use opencv once again to go through a premade dataset and find objects that it could recognize in that image. Once it gets those objects, it uses some premade functions
to make a bounding box around the object and also declare what it is inside the box. The text to speech software, will then take that object name and output it through
speakers.(You need usb speakers puggled into the jetson nano and then need to set it as your output device btw). This will be repeated until you are to press Ctrl + C.
Thank you for listening to my what I have made for you. I hope you enjoy playing around with it!

The only things I needed for this project is opencv and python3. Which come with the rest of the project. If opencv doesnt work try sudo installing it....
