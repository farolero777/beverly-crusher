beverly-crusher
===============

![Dr. Crusher portrait by aliceazzo.](http://www.electronoob.com/images/Beverly_Crusher_by_aliceazzo.jpg "The fantastic Beverly Crusher artwork is by aliceazzo and the link to her deviantart is http://aliceazzo.deviantart.com/ - This work is entirely hers and I havent asked permission to associate it with my application, website, nor have I even spoken to this person before so please keep in mind that this image is not part of the same license as this software.")

Image &copy; [aliceazzo](http://aliceazzo.deviantart.com/ "aliceazzo's deviant art page.").


beverly-crusher (build 27) [http://electronoob.com]
===================================================
Released under the terms of the MIT license.
Copyright (c) 2014 electronoob.
All rights reserved.


**Syntax**

	To output file direct to alsa default device:

	./crusher --input mysing.raw --alsa


	To write conversion to file:

	./crusher --input mysing.raw --output crushed.raw


**compile**

gcc main.c alsa.c -lasound -lm

**about**

i wanted a tool for crushing audio data for use with a microcontroller but i couldn't find one; so i'm writing one.


the idea is very simple actually.

right now the code is incomplete and is very early days of development, it can take a RAW audio data and play it back crushed to 1bit. 

