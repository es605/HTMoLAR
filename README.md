<h1>HTMoL &#150; AR plugin</h1>

<br>
&emsp; <b>HTMoL &#150; AR plugin</b> is an initiative from <a href=https://www.researchgate.net/profile/Eric_Sliwinski target=&quot;_blank&quot;><strong>Eric P. Sliwinski</strong></a>, <a href=http://www.leygroup.ch.cam.ac.uk/group-members/postdoctoral-research-associates-2/dr-mikhail-kabeshov target=&quot;_blank&quot;><strong>Mikhail A. Kabeshov</strong></a> and <a href=http://www.leygroup.ch.cam.ac.uk/steve-ley target=&quot;_blank&quot;><strong>Steven V. Ley</strong></a> for the web-based visualisation, analysis and report of computed structures or crystallographic data.

<br>

Originally developed as a part of the <a href=http://www.leygroup.ch.cam.ac.uk/research/science-gateway target=&quot;_blank&quot;><b>Organic Chemistry Science Gateway</b></a>,
the web-based application takes advantage from Augmented Reality technology to allow the user to quickly access specific molecular structural data with visualisation among a large number of computed structures,
from any computing device equipped with a camera and an Internet connection.

The web-based viewer can also be employed for the semi-automatic animation of reaction pathways by linear interpolation of atom coordinates between consecutive computed reaction steps.
<br>

<a href=https://es605.bitbucket.io/Staudinger/redirect2viewer.html target=&quot;_blank&quot;><strong>DEMO for computed structures</strong></a>

<a href=https://es605.bitbucket.io/Staudinger/redirect2index.html target=&quot;_blank&quot;><strong>DEMO for animated reaction pathways</strong></a>

<br>
<h2>Screen Captures</h2>

<p align="center">
    <img src="http://es605.bitbucket.io/HTMoLAR/SC013.png">
</p>
    <br>
<p align="center">
    <img src="http://es605.bitbucket.io/HTMoLAR/AR.png">
    <br>
</p>
<br>
<br>
<h2>Video Demonstration</h2>
<p align="center">
    <a href="http://www.youtube.com/watch?feature=player_embedded&v=QWY7UikT42g" target="_blank"><img src="http://img.youtube.com/vi/QWY7UikT42g/0.jpg" width="480" height="360" border="1" /></a>
</p>
<br>

<h2>Browser Support</h2>

You will need a [**HTML5**](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5), [**WebGL**](http://caniuse.com/#search=WebGL), [**getUserMedia()**](http://caniuse.com/#feat=stream) compatible web browsing software. We would therefore recommend one of the latest version of Google Chrome&#8482; or Mozilla FireFox&#8482; (recommended).

<br>
<h2>Touch Controls</h2>

<p align="center">
    <img src="http://es605.bitbucket.io/Staudinger/svg/touch.svg" alt="http://es605.bitbucket.io/Staudinger/Pictures/touch.png">
</p>

<br>
<h2>Mouse Controls</h2>

<p align="center">
    <img src="http://es605.bitbucket.io/Staudinger/svg/mouse01.svg" alt="http://es605.bitbucket.io/Staudinger/Pictures/mouse01.png">
</p>

<h4>or</h4>

<p align="center">
    <img src="http://es605.bitbucket.io/Staudinger/svg/mouse02.svg" alt="http://es605.bitbucket.io/Staudinger/Pictures/mouse02.png">
</p>

<br>
<h2>Other Features</h2>

<p align="center">
    <img src="http://es605.bitbucket.io/Staudinger/Pictures/featuresHolo.png">
</p>

<h5>&bull; Play / Pause Animation</h5>
Reaction pathways are animated by linear interpolation of each atom location between consecutive computed structures. When applicable, you can pause the animation at any time by using the Play/Pause button. You can also look over any specific structure on the reaction pathway with the help of the interactive progress bar.

<h5>&bull; Reset View</h5>
You can reset the view to its default state by using this button.

<h5>&bull; Hide / Show Hydrogens</h5>
You can toggle hydrogen visibility at any time by using the Hide/Show Hydrogens button.

<h5>&bull; Monitor</h5>
> <strong>N.B.</strong>   This feature is only available when the animation is paused.
<br>
This feature allows you to monitor structure parameters such as a single atom coordinates, interatomic distances, angles or dihedral angles for any specific structure, by clicking on the atoms.

<h5>&bull; Save XYZ</h5>
> <strong>N.B.</strong>   This feature is only available on desktops and laptops, when the animation is paused.
<br>
This feature allows you to save the Cartesian coordinates of all visible atoms for a specific structure as an *.xyz file.

<h5>&bull; Center on Atom</h5>
> <strong>N.B.</strong>   This feature is only available on desktops and laptops, when the animation is paused.
<br>
You can center the 3D-molecular structure on a specific atom by right-clicking on it.

<h5>&bull; Navigate</h5>
When applicable, you can access the 3D representation of other computed structures by using one of the arrow buttons located on each side of the page. The 3D representation of a specific structure can also be accessed
<i>via</i> the  <strong>Augmented Reality Controls</strong> described below.

<br>
<br>
<h2>Keyboard Shortcuts</h2>
> <strong>N.B.</strong>   This feature is only available on desktops and laptops.
<br>
<p align="center">
    <img src="http://es605.bitbucket.io/Staudinger/svg/shortcutsHolo.svg" alt="http://es605.bitbucket.io/Staudinger/Pictures/shortcutsHolo.png">
</p>

Keyboard event listener was also implemented, providing basic shortcuts for some of the above features.

<br>
<h2>Leap Motion&#8482 Controls</h2>
> <strong>N.B.</strong>   This feature is only available on desktops and laptops.
<br>
<p align="center">
    <img src="http://es605.bitbucket.io/HTMoLAR/LeapHandNEW.png">
</p>
<br>
The camera position (rotation, zoom) can also be controlled <i>via</i> a Leap Motion&#153; sensor device. Just wave your hand over the device to begin moving the camera around the molecular structure. Zoom controls are also accessible by pinching your index and thumb fingers.

<br>
<br>
<h2>Augmented Reality Controls</h2>
> <strong>N.B.</strong>   This feature is not available on Apple iOS devices at the moment, as the <a href=http://caniuse.com/#feat=stream target=&quot;_blank&quot;><strong>getUserMedia() API</strong></a> is not supported.

<br>

<p align="center">
    <img src="http://es605.bitbucket.io/Staudinger/svg/AR.svg" alt="http://es605.bitbucket.io/Staudinger/Pictures/AR.png">
</p>

If you wish to try Augmented Reality controls, you will need a good quality printing of the provided <strong>AR</strong> marker, a good camera (with autofocus) and to allow the camera request.

You can also navigate to the 3D representation of a specific structure <i>via</i> <strong>AR</strong>.
Upon termination of the video stream, when applicable, the main window should update to display the structure associated to the <strong>AR</strong> marker being detected.

<br>
<h2>Holographic Display</h2>
> <strong>N.B.</strong>   Zoom controls are disabled for this feature.
<br>
<br>

<p align="center">
    <a href="http://www.youtube.com/watch?feature=player_embedded&v=3U3e2PEFNzA" target="_blank"><img src="http://img.youtube.com/vi/3U3e2PEFNzA/0.jpg"alt="http://es605.github.io/HTMoLAR.png" width="480" height="360" border="1" /></a>
</p>
<br>

If you wish to try the Holographic Display, you will need a pyramidal mirror made from a semi-reflective transparent material. This mirror can be constructed, for example, by cutting <a href=https://leyscigateway.ch.cam.ac.uk/staudinger/Markers/TemplateA4.pdf target=&quot;_blank&quot;> this<strong> template</strong></a> into a thick (240 &#8212; 600 &#181;m) acetate sheet.

For better performance, we would recommend to use that feature in a darkened room and to switch your web-browser to full-screen (by pressing F11).

<br>

<h2>Publications</h2>

* <a href=https://www.thieme-connect.com/products/ejournals/abstract/10.1055/s-0035-1562579 target=&quot;_blank&quot;>  Combination of Enabling Technologies to Improve and Describe the Stereoselectivity of Wolff–Staudinger Cascade Reaction</a>

* <a href=https://www.thieme.de/en/thieme-chemistry/augmented-reality-as-an-enabling-tool-in-organic-chemistry-104150.htm target=&quot;_blank&quot;>  Augmented Reality as an Enabling Tool in Organic Chemistry</a>

* [Journal innovations – the next step is augmented reality?](http://www.ch.imperial.ac.uk/rzepa/blog/?p=16710)

* [Chem@Cam Issue 55, Summer 2017](http://www.ch.cam.ac.uk/files/chematcam/Chem%40CAM%2055%20webstite.pdf)

* [Organic Chemistry Portal](http://www.organic-chemistry.org/abstracts/lit5/610.shtm)

<br>

<h2>Acknowledgements</h2>

*   <a href=http://www.leygroup.ch.cam.ac.uk/group-members/phd-students/daniel-fitzpatrick target=&quot;_blank&quot;> Daniel Fitzpatrick </a>

*   <a href=http://www.ch.cam.ac.uk/person/rmt35 target=&quot;_blank&quot;> Dr Richard Turner </a>

*   <a href=https://github.com/mrdoob target=&quot;_blank&quot;> Mr Doob </a>, <a href=http://threejs.org target=&quot;_blank&quot;> THREE.js </a>

*   <a href=http://cg.skeelogy.com target=&quot;_blank&quot;> Skeel Lee </a>

*   <a href=https://github.com/jcmellado target=&quot;_blank&quot;> Juan Mellado </a>

*   <a href=https://stemkoski.github.io/Three.js/ target=&quot;_blank&quot;> Lee Stemkoski </a>

*   <a href=https://github.com/leongersen target=&quot;_blank&quot;> Leon Gersen </a>

*   <a href=http://github.com/t4t5/ target=&quot;_blank&quot;> Tristan Edwards </a>

*   <a href=https://github.com/eligrey/ target=&quot;_blank&quot;> Eli Grey </a>

*   <a href=http://greensock.com target=&quot;_blank&quot;> GreenSock </a>

*   <a href=http://github.com/leapmotion/ target=&quot;_blank&quot;> LeapJS </a>

*   <a href=http://stackoverflow.com/ target=&quot;_blank&quot;> Stackoverflow </a>


<p align="center">
    <span>sliwinski.eric@orange.fr</span> &bull; 2015 &#150; 2018
</p>
