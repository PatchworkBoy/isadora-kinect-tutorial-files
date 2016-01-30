# isadora-kinect-tutorial-files
A fork of Tutorial Files for using MS Kinect with Troikatronix Isadora via Processing 2.2.1

Community requested that multiple skeleton support and feed switching via OSC be added.

Refer to [this post](http://troikatronix.com/community/#/discussion/2462/kinect-isadora-tutorials-now-available)

[Video Walkthrough](https://www.youtube.com/watch?v=0HY5U6QSyhM) by [VJ_Skulpture](https://vjskulpture.wordpress.com)

##To Do
In no particular order...
- [ ] Multiple skeleton visualisation
- [ ] Multiple skeleton transmission via OSC
- [x] OSC Receiver functions to switch video feeds
- [x] OSC Receiver functions to switch skeleton drawing on/off
- [x] OSC Receiver functions to switch mirror mode on/off

###WARNINGS!
If you start the processing sketch with camera in RGB mode, you CANNOT USE IR MODE.
If you start the processing sketch with camera in Depth mode, you CANNOT USE IR MODE.
If you start the processing sketch with camera in User mode, you CANNOT USE IR MODE.

If you start the processing sketch with camera in IR mode, you CANNOT USE RGB MODE.

Also, please note & be aware of the open issue relating to [iso_callbacks & isochronous transfer errors](https://github.com/PatchworkBoy/isadora-kinect-tutorial-files/issues/1)...

##Original Release Statement
>Dear Community,
>
>I'm happy to present to you a three-part series on working with the Kinect using 
>Isadora. These tutorials, written by Montgomery Martin, were based on techniques 
>presented by Mark Coniglio during Troika Ranch’s Live-I Workshop in July 2015. 
>They now live on the main TroikaTronix site.
>
>Over the three part tutorial, we discuss how to use the open-source sketchbook 
>application Processing to act as a communication bridge between the Kinect 
>hardware and Isadora.
>
>[Part 1](http://troikatronix.com/support/kb/kinect-tutorial-part1/) serves as an 
>introduction to the Kinect and what it can offer, along with some important points 
>about particular versions of the camera:
>
>In [Part 2](http://troikatronix.com/support/kb/kinect-tutorial-part2/) of this 
>tutorial, we will learn how to download, install, and configure Processing to receive 
>full body motion data and infrared video from an Xbox Kinect motion sensor. 
>
>In [Part 3](http://troikatronix.com/support/kb/kinect-tutorial-part3/), you will learn 
>how to set up Isadora to receive the OSC and Syphon feeds that Processing broadcasts 
>from the Xbox 360 Kinect camera.
>
>Thank you especially to the rest of the TroikaTronix team for their valuable feedback 
>and assistance in compiling, reviewing, and editing these tutorials: Mark Coniglio, 
>Jamie Griffiths, and Ryan Webber, Michel Weber and Graham Thorne.
>
>Cheers, and enjoy!
>
>Sincerely,
>Monty Martin and The [TroikaTronix](http://troikatronix.com/community/) Team
