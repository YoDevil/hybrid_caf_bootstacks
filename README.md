Bootstacks Hybrid for LG G2 CAF
=====================================

Variant  | Aboot/Laf Version | Bootstacks Version | Loki/Bump Support   | Assert zip | CM Version
--------:|:-----------------:|:------------------:|:-------------------:|:----------:|:------------
D800     | KitKat 	         | Lollipop           | Only Bump		    | Yes  	     | CM 12.1 CAF
D801     | KitKat   	     | Lollipop           | Only Bump		    | Yes  	     | CM 12.1 CAF
D802     | KitKat	   	     | Lollipop           | Only Bump 		    | Yes 		 | CM 12.1 CAF
D803     | KitKat	   	     | KitKat             | Only Bump 		    | Yes 		 | CM 12.1 CAF
D805/6   | KitKat	   	     | Lollipop           | Only Bump 		    | Yes 		 | CM 12.1 CAF
F320     | KitKat     	     | Lollipop           | Only Bump		    | Yes  	     | CM 12.1 CAF
LS980    | KitKat  	   	     | Lollipop           | Only Bump		    | Yes		 | CM 12.1 CAF
VS980    | KitKat 	   	     | Lollipop           | Only Bump		    | Yes 		 | CM 12.1 CAF

<b>-FAQ-</b> <br/> <br/>
<b>What is bootstrap?</b>  <br/>
It's a set of images, that are essential for your device. These hybrid bootstracks use all the images from lollipop, except aboot & laf, that are from kitkat. So, we can have bump working with LP partitions.
	
<b>What is in it? (Except D803)</b> <br/>
-Aboot (KK)<br/>
-Dbi (LP)<br/>
-Laf (KK)<br/>
-Modem (LP)<br/>
-Rpm (LP)<br/>
-Sbl1  (LP)<br/>
-tz (LP)<br/>

<b>What is assert?</b> <br/>
Assert is a command line in zip script, it checks if you're flashing a compatible bootstrap with your device.
	
<b>Why it only supports bump?</b> <br/>
Because I updated all the aboot files to KK, and only JB supports loki.
	
<b>Why you updated aboot to KitKat?</b> <br/>
Because KK bootloader is more reliable, and I can merge the original kernel cmdline.

<b>I can't enter in recovery, why?</b> <br/>
My aboot files are the most recent KK versions, some of them have a new way to enter in recovery:<br/>
<b>-Old Way:</b> Hold <b>power + vol down</b>, then, release and hold <b>power + vol down again</b>.<br/>
<b>-New Way:</b> Hold <b>power + vol down</b>, then, release and hold <b>vol up + vol down</b>.

<b>How D803 & D805/6 bootstacks are available, if they are stuck on KK?</b> <br/>
<b>-D805/6</b> share the same hardware with D802, except MODEM. So, it uses D802 bootstacks and an edited D802 baseband with d805 modem files. Also, the KK aboot/laf are from D805, this way it doesn't mess kdz update.<br/>
<b>-D803</b> is using D803 KK bootstacks, except by the modem, that is the same from D801, but, edited with D803 modem files.
	
<b>Have any issue?</b> <br/>
[Report Here] (https://github.com/danielstuart14/bootstacks/issues)
