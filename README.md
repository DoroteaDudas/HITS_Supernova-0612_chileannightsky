# 0612 - Chilean Night Sky (Light Pollution)

## Short Description

<table align="center">
    <tr>
    <td align="left" style="font-style:italic; font-size:12px; background-color:white">Explore the impact of artificial lights!<br>
Stars can be best seen in dark places.<br>
Use the slider on the touchscreen to explore the night sky with and without artificial light.
</td>
    </tr>
</table>

The application shows the effect light pollution has on the night sky.
The user can compare two photographs, one taken in a Chilean desert and the other in Germany, to observe how visible the stars in the sky are. The absence of light sources results in a clearer view of the sky. The Orion constellation is marked on both photographs as a reference. The photograph taken in Chile also shows the orange VLT (Very Large Telescope) laser beam used for guide stars.

The slider can be used to blend between or compare the pair of images. Using the upper two buttons on the right, the image pair can be aligned according to the Orion constellation, or just be kept as seen from the two locations images were taken at. The lower two buttons on the right change the slider from a blend mode to a clean divide mode between the two images. Three buttons in the lower left corner allow the user to restart the application, change the language (English or German) and get some help. 

This application is used at the [ESO Supernova Planetarium and Visitor Centre](https://supernova.eso.org/?lang=en), Garching b. München.  
For more details about the project and how applications are run and managed within the exhibition please see [this link](https://gitlab.com/HITS_Supernova/overview).   

## Requirements / How-To

A browser with a WebGL support is needed to run the interactive (start `WebGL/webgl_LightPollution.html`).  
If no touchscreen is available the interactive can be operated with the mouse.

## Detailed Information

#### URL parameters

*lang* - language parameter (english as default if not there)  


#### Sky photographs

1) Paranal Observatory: Constellation Orion setting over VLT / Paranal Observatory in Chile, with laser guide star beam visible

- raw file: `WebGL/Images/dsc5386.nef`
- date & time: 2017-03-22 00:40:55 CLST (UTC-03:00)
- GPS location: 24° 38' 26.2" S, 70° 23' 18.2" W

2) Königstuhl: Constellation Orion setting over Heidelberg in Germany, looking down from Königstuhl on a clear winter night

- raw file: `WebGL/Images/dsc7942.nef`
- date & time: 2018-02-14 00:00:13 CET (UTC+01:00)
- GPS location: 49° 24' 15.5" N, 8° 43' 34.5" E

See EXIF data for further details.


## Credits

This application was developed by the ESO Supernova team at [HITS gGmbH](https://www.h-its.org/en/).  
Idea and coding by Dorotea Dudas.  
Photographs and advising by Volker Gaibler. 

#### Code Licensing

* This code is licensed as: [MIT license](LICENSE)
* MIT license:
    * *jQuery* [source](https://jquery.com/)
    * *Three.js* by Mr.doob (Ricardo Cabello) [source](https://threejs.org/)
    * *Image Blend/Divide shader* (intrinsic) by Dorotea Dudas
 

#### Image Licensing

* CC BY 4.0:
    * Sky photographs by Volker Gaibler
    * Info/Help Screen images by ESO / HITS gGmbH
    * Icons (except blue navigation icons) by Dorotea Dudas
    * Blue Navigation icons by Design und mehr GmbH







