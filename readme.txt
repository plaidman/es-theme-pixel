Theme 'pixel' v1.4 by Rookervik edited by bebeidon for GPi handheld and other small 4:3 displays (320x240).

Default version contains meta-data in bottom right box, the alternate pixel_desc.xml contains description in that box.
Per default this theme uses the screenshot if there is no video.

If video is the prefered gamelist style one should comment the following part in the <view name="detailed, video"> section of the pixel.xml (or pixel_desc.xml)

<image name="md_image">
			<pos>0.766 0.322</pos>
			<maxSize>0.366 0.480</maxSize>
			<origin>0.5 0.5</origin>
		</image>
    
like this:

<!--<image name="md_image">
			<pos>0.766 0.322</pos>
			<maxSize>0.366 0.480</maxSize>
			<origin>0.5 0.5</origin>
		</image>
		-->

Then the Screenshot will be shown and after a delay of 4 seconds the screenshot is hidden and the video shown, if you don't comment the md_image part, the picture will stay behind while the video is playing which can be ugly in some cases (when screenshot is a different format/resolution than video).

This theme is per default set to show the European and Japanese Consoles and names. This can be changed by setting the proper folder name like: snesUS to snes and snes to snesE, to get the North American SNES. The same goes for PCEngine and Turbografx-16.


To set the icons in the Retropie menu to Pixel icons copy them from the retropie folder to /home/pi/Retropie/retropiemenu/icons/






Thanks to ChoccyHobNob for providing the art for Custom collections with his cygnus theme.
Thanks to muriani for the super-sexy Sega CD logo! 
Thanks to Omnija for helping me fix some code errors.



License

=======





ALLOWED:      	- Share and duplicate as it is

              		- Edit, alter, change it



REQUIREMENTS: 	- Attribution, give credit to the creator

              		- Indicate changes to it

              		- Publish the changes under the same license



PROHIBITED:   	- Commercial distribution





LOGO NOTICE:


The used logos and trademarks are copyright of their respective owners.
