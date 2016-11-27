---
layout: post
title: "Arduino Based PC Ambient Lighting"
date: 2011-02-08
---

Arduino Based PC Ambient Lighting
I really like the concept of ambient lighting systems which synchronize with entertainment to create a great immersive experience. And since I had a RGB led strip lying around I decided to use my Arduino and a Processing sketch to create such a system for computers which really turned out great!

Here is a video of my setup and a nice demo of it working with a Star Wars video clip:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/Am55k0k9eq8/0.jpg)](http://www.youtube.com/watch?v=Am55k0k9eq8)

Materials:
If you would like to setup this system, it is quite simple and does not require any Arduino shields. The materials you will need other than an Arduino are:
+RGB LED Strip (<=$15.95): You can get really cheap ones but I went with this Sparkfun LED strip due to ease of shipping (http://www.sparkfun.com/products/10261).
+ULN2003A (~$00.63): This chip is a transistor array for driving the LED strip which requires 12V signals with the 5V digital signals from the Arduino (order from DigiKey: http://www.digikey.com)
+12V DC supply ($5.95-$18.99): I am very sure you can get really cheap wall to 12V DC supplies but I was lazy and snipped off the end off a Garmin 12V car GPS charger (http://www.amazon.com/Garmin-AC-Vehicle-Power-Adapter/dp/B0011V1KZ6/ref=sr_1_2?ie=UTF8&qid=1297231222&sr=8-2) Another charger which is much cheaper (http://www.pololu.com/catalog/product/1466)

Schematic:
The LED driver circuit is extremely simplified due to the ULN2003A chip which eliminates the need for a separate transistor circuit for each R, G and B channel of the LED. Here is the schematic:

