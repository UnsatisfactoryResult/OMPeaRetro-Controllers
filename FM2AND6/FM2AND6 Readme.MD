## **What is it, and what's it do?**

The FM2AND6 is a custom controller built into a Saturn style shell designed for the Fujitsu FM Towns series of computers and Marty consoles. While it is specifically designed for FM Towns, 2 Button Mode is compatible with the following Japanese PC platforms as well:

**CONFIRMED**
* Fujitsu FM-7/NEW7/77/77AV Series
* MSX/MSX2/MSX2+/MSX Turbo R Series
* NEC PC6000 Series
* NEC PC88 Series (through 9 pin mouse port, may require soundcard with joystick ports depending on model)
* NEC PC98 Series (through 9 pin mouse port, may require miniDIN adapter for mouse port, or soundcard with joystick ports depending on model)
* Sharp X68000 Series

**CONFIRMED BUT REQUIRE ADAPTER**
* Sega SC3000/SG1000/Master System (adapter available on OMPeaRetro.com)
* Sharp X1 Series (adapter available on OMPeaRetro.com)
* Tomy ぴゅう太 (Pyuuta)/Tutor Series (small numbers of adapters may be available on OMPeaRetro.com in the future)
* Toshiba Pasopia/Pasopia7/T100 Series (requires JOYPAC2, XPAC2, or similar)

**UNCONFIRMED**
* Hino CEFUCOM-21 (Sanyo PHC-25 compatible with built in joystick ports)
* Hitachi MB-S1/10AV (the only model in the series with built in joystick ports)
* National JR-200 (I own one, but need to repair and test)
* Sharp MZ-800 (European only successor to the MZ-700, dipswitch 1 = off, may require Sharp X1 adapter)
* Sharp MZ-2500 Series
* Sony SMC-777 Series (I own one, but need to repair and test)

**UNCOMFIRMED AND COMPLICATED**
* Hitachi MB-S1 Series excluding the /10AV (require joystick interface card or MPC-PJ01 expansion)
* Philips/Radiola/Schneider VG5000μ (released only in France, requires VG5200 or VG5216 expansions)
* Sanyo PHC-25 (requires the PSG-01 expansion)
* Seiko MAP-1010 (Sanyo PHC-25 compatible, requires the MAP-1030 expansion)

There are other platforms it may work on as well. If an FM Towns controller works on it then the FM2AND6 should work as well, and if an MSX controller works on it then the FM2AND6 might work on it. Systems marked **CONFIRMED** have been tested by myself or others. A big thanks to KTJDragon at KTJDragon.com for posting info about some of the more obscure systems on his site.

6 Button Mode is specific to the FM Towns. A small handful of games make use of more than 2 buttons:

* Blandia Plus (3 buttons)
* PuLiRuLa (3 buttons)

* Fatal Fury (4 buttons) (Extremely rare and undumped as of right now, but word is that a dump is coming)
* Samurai Spirits (4 buttons) (Requires 4MB RAM and 486 CPU, not playable on Marty)

* Super Street Fighter II (6 buttons) (Requires 4MB RAM, playable on Marty with RAM expansion and turning "Raster" off in menu)

------------------------------------
## **What about other 6 button platforms?**

The X68000 is the only other platform with some official games that make use of more than 2 buttons, but they did not release their own controller for this. Instead they relied on the game creators to release their own solutions.

* Capcom released an adapter to make use of the 6 button Genesis controller for their 2 Street Fighter II releases
* Chelnov came with a small adapter for use with the 3 button Genesis controller.
* Magical Company released their own controller for use with Fatal Fury 2 and Special

These three groups all used different protocols for their games so there isn't a simple one controller solution I personally can make. I do have a working prototype that combines the FM Towns 6 button and the Capcom adapter/6 button Genesis protocols into one controller. The Fatal Fury games are supposed to recognize a 6 button Genesis controller with a Chelnov style adapter, but it won't recognize my Retro-Bit licensed controller, so I will test with an original eventually.

----------------------------------
## **Why use a Saturn style controller?**

It's awesome! I was a Sega kid growing up, and the Japanese Saturn controller is definitely a top 3 controller for me. It also has the perfect amount of buttons I needed to create the FM2AND6. 

---------------------------------------------------------
## **How are the buttons laid out, and what's this Derek Mode?**

There's a graphic in the pictures folder showing an overview of the modes. The center 2/6 Mode button is a latching pushbutton switch. In the extended position 2 Button Mode is active, in the depressed position 6 Button Mode is active. Some FM Towns games do not work properly with a 6 button controller, hence the need to be able to swap back and forth.

If you look at the layout graphic closely, you'll notice Derek Mode. This only affects 2 Button Mode, and it keeps the A Button on the left and the B Button on the right. The controller ships in Standard Mode. If you would prefer Derek Mode then you'll need to open the controller and press down the hidden pushbutton switch.

---------------------------------
## **Who manufactures them, and where?**

* The PCBs and SMD assembly takes place overseas. I only select major brands for components; such as, Texas Instruments, Panasonic, Samsung, Rohm, etc. A 2U thick ENIG (gold) finish is used on the exposed copper for maximum corrosion resistance.
* The 2/6 button mode switch cap is 3D printed overseas.
* The controller cases, cables, and switches are all off the shelf items I purchase from overseas.
* The logos I design and have printed locally.
* Once I have all the parts on hand in the US, I solder on the cables, switches, and trigger button PCBs. Everything then gets cleaned of flux and any debris.
* At this point we enter the testing and assembly phase. I partially assemble it so that I can test that Derek Mode functions properly. Everything gets fully assembled and tested in Standard Mode. If all is well, I apply the logos, and put it in its box.
* There are a few modifications I make to the cases themselves prior to assembly at some point in the process. The testing is also to ensure these modifications are within my spec, and will be adjusted if needed.
* I test one more time before I ship out for a triple sanity check.

----------------------------------------------------------------------------------
## **Will it work on some really obscure platform that nobody has heard of in 40 years?**

Possibly? Send me an email. There are some very unique controller setups out there on old Japanese PCs. The Sharp MZ-700 series, Sord M5, and Bandai RX-78 are pretty non-standard, for example. I do plan to add support where I can via plug in adapters, but this will take some time.

I do have a few adapters available that expand the compatibility.

--------------------------------------------------------------------
## **Will this work on Western computers like the TI 99/4A or Atari 2600?**

No. I could make adapters for it, but I plan to offer a different solution for Western computers at a later time.

----------------------------------
## **I don't need all of those buttons.**

I'm currently testing a prototype that also uses the Saturn shell, but has 2 buttons and up mapped to the ABC buttons. XYZ are actually autofire enable switches for the button under it, and the start button is an autofire frequency selector. 
