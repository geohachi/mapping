# Satellite images for mapping

* Several sattelite images are available in mapping tools. (iD Editor, geom, etc.)
* Most mapping tasks instruct us to use Maxar image. 
* Bing is older!

# Difference of satellite images

See following two images of the same place. Fig.1 is Bing and Fig.2 is Maxar.
You can notice that the area of land is larger in Maxar.

Fig.1 Bing image
![Bing1](/satellite/Bing1.JPG)

Fig.2 Maxar image
![Maxar1](/satellite/Maxar1.JPG)

# Close-up

Please look at the following close-up picture of lower right of the area.
Can you believe they are the same area?

Fig.3 Bing image (close-up)
![Bing2](/satellite/Bing2.JPG)

Fig.4 Maxar image (close-up)
![Maxar2](/satellite/Maxar2.JPG)

# How to switch satellite images
It depends on the editor you are using.
I will explain about iD Editor.

In the editor, press 'B' key that brings up Background menu as shown in Fig.1.
In my case, the following list is shown.
* Bing aerial imagery
* Satellite and aerial imagery.
* Esri World Imagery
* Esri World Imagery (Clarity) Beta
* Mapbox Satellite
* Maxar Premium Imagery (Beta)
* Maxar Standard Imagery (Beta)

You can check those images.
Some are blur and some may have cloud and you cannot see the ground.
The color may differ because of the time and season the image taken.


As I mension already, Maxar image is so-so clear and the latest that is the most important thing for mapping.
So basically, you want to use Maxar image.
(I don't see any difference between "Maxar Premium Imagery" and "Maxar Standard Imagery", so I always use premium one.)
But in case you cannot see the building clearly, you can tempolary switch background image to Bing or even other satellite to clarify the surface of the ground. (By using Ctrl-B, you can go back and forth the last two images.)

## Adjusting imagery offset
You may notice that there is imegery offset between two.
You can cancel it by using "adjust-imagery-offset" function in the menu if you want.
You need to scroll-down to reach this option. See Fig.5.

To adjust offset, drag gray area around the box by mouse cursor while the left button is pressed.
I recommend you adjust it only for Bing image if necessary, and keep 0,0 for Maxar.

Fig.5 Imagery offset control
![ImageryOffsetControl](/satellite/adjust-imagery-offset.JPG)

## Adjusting image brightness/contrast
You can change image's brightness/contrast/etc. by adjusting "Display Option".
See Fig.6.

Fig.6 Display Option
![DisplayOption](/satellite/display_option.JPG)





