Bootstacks Hybrid for LG G2 CAF
=====================================

Variant | Aboot Version     | Bootstacks Version | Loki / Bump Support 	   | Assert zip 	    | CM Version
-------:|:-----------------:|:------------------:|:-----------------------:|:------------------:|:------------
D800    | KitKat 	    	| Lollipop           | Only Bump			   | Yes  			    | CM 12.1 CAF
D801    | KitKat   	    	| Lollipop           | Only Bump		  	   | Yes  				| CM 12.1 CAF
D802    | KitKat	   		| Lollipop           | Only Bump 		 	   | Yes 				| CM 12.1 CAF
F320    | KitKat     		| Lollipop           | Only Bump		   	   | Yes  				| CM 12.1 CAF
LS980   | KitKat  	   	 	| Lollipop           | Only Bump		  	   | Yes				| CM 12.1 CAF
VS980   | KitKat 	   	 	| Lollipop           | Only Bump			   | Yes 				| CM 12.1 CAF

<b>-FAQ-</b> <br/> <br/>
<b>What is bootstrap?</b>  <br/>
It's a set of images, that are essential for your device. These hybrid bootstracks use all the images from lollipop, except aboot, that is from kitkat. So, we can have bump working with LP partitions.
	
<b>What is in it?</b> <br/>
-Aboot (KK)<br/>
-Dbi (LP)<br/>
-Laf (LP/KK)<br/>
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
	
<b>Have any issue?</b> <br/>
[Report Here] (https://github.com/danielstuart14/bootstacks/issues)
