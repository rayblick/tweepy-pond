# Tweepy-Pond

I like ponds. This project was undertaken so I could monitor my homemade pond. The goal is to detect animal movement, take a photo of the ellusive beast along with some simple measurements (pond temp and air temp) and post it to its own twitter account. I am very curious to see if the water is being used by snakes. I like snakes.

You can follow the development of this project, and eventually its application, at https://twitter.com/tweepy_pond. This project also gave me an entry point into using the Raspberry Pi (and hopefully a bridge to Linux), building simple circuits, learning about near infrared cameras, and writing a little code in python to get the job done. 

Most of the brains behind this project can be attributed to the CamJam EduKitSensor #2 pack (http://camjam.me/) and their associated worksheets. I simply mashed the lot together and added the camera/tweeting functions (which can be attributed to, in part, to the PiCamera documentation http://picamera.readthedocs.org/en/release-1.9/.)

### Going headless 
I am using the Pi outside the house, so I needed to have remote access via another computer. I followed the raspberry pi tutorial found here: http://www.raspberrypi.org/documentation/remote-access/vnc/. It was pretty straight forward to implement the vncboot file on start up. 

### The electronics 
I followed the CamJam EduKitSensor worksheets to install the PIR motion detector, LEDs, temperature probes and the light resistor. I also used their worksheets to get them to run. However, I did modify several functions and the main loop to integrate the operation of all the bits so that they fire at the right time (more below in 'the code'). The temperature probes (w1) have a unique serial number and can be wired together directly (yellow - yellow, black - black, red to red). 

The parts to carry out this project included, the raspberry pi, pi noir camera and the wifi adaptor from Aus Pi Technologies Australia (http://www.buyraspberrypi.com.au/), x2 EduKits from ThePitHut (http://thepihut.com/), breadboard connects from Adafruit (http://www.adafruit.com/). Several other bits and pieces are required, such as wire strippers, proto board, hook up wire... and a power source (To be decided. I am currently testing the longevity of a 9000mAh power bank. Perhaps a conversion to solar after its set up. I like solar power.)

### The code
Coming soon
