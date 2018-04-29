# ArcheryRender
Packages used in rendering Amice Lis project on archery. Unity 2018 
## Assets
We used the Native Post-Processing Stack from Unity . Specifically we ignored some effects and replaced them with more endearing ones.

 **Post-Processing**

* *Obscurance* is a screen-space ambient obscurance (SSAO) image effect for Unity.
Works better with Deffered rendering
* *Aura* https://github.com/raphael-ernaelsten/Aura
* *Hex Bokeh* , Blur : is an image effect for Unity which simulates depth of field with hexagonal apertures.
The original technique was described by L. McIntosh. The shader in this package is a straightforward implementation of his technique with a few minor tweaks.
* *Tonemapping & Color Grading*
* Global Illumniation* from https://github.com/sonicether/SEGI

*BLOOM* : a local simulation of the light scattering into the surrounding medium
* *Anti-Aliasing*  : I used SIGGRAPH proposal of SMAA : Sub-pixel Morphological Anti-Aliasing , a shader-based anti-aliasing algorithm created  by Jorge et.al https://github.com/iryoku/smaa.
Works with the deferred & forward rendering paths, in gamma or linear color space, with Directx 9, Directx 11 and OpenGL targets.
Now added to *The Unity Cinematic Image Effects* http://u3d.as/mHd
*  *SE Screen-Space Shadows* http://www.sonicether.com/screenspaceshadows/
provides screen-space raytraced shadows for directional lights for sharp, detailed contact shadows. It can capture details in shadows that would otherwise be missed using traditional shadow maps alone.

 ## Shaders
 I used the Amplify Shader Editor, a visual programming tool for making shaders
 The grass used has high LOD

 https://cartrdge.com/maxgit/black-forest
 
 ![alt text](https://github.com/jonas-kgomo/ArcheryRender/blob/master/okayman.jpg "Logo Title Text 1")


