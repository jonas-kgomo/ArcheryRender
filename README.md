# ArcheryRender
Packages used in rendering Amice Lis project on archery. Unity 2018 
## Assets
We used the Native Post-Processing Stack from Unity . Specifically we ignored some effects and replaced them with more endearing ones.

 **Post-Processing**

* Obscurance is a screen-space ambient obscurance (SSAO) image effect for Unity.
Works better with Deffered rendering
* Hex Bokeh , Blur : is an image effect for Unity which simulates depth of field with hexagonal apertures.
The original technique was described by L. McIntosh. The shader in this package is a straightforward implementation of his technique with a few minor tweaks.
* Tonemapping & Color Grading 
* Anti-Aliasing  : I used SIGGRAPH proposal of SMAA : Sub-pixel Morphological Anti-Aliasing , a shader-based anti-aliasing algorithm created  by Jorge et.al https://github.com/iryoku/smaa.
Works with the deferred & forward rendering paths, in gamma or linear color space, with Directx 9, Directx 11 and OpenGL targets.

 ## Shaders
 I used the Amplify Shader Editor, a visual programming tool for making shaders
 The grass used has high LOD

 https://cartrdge.com/maxgit/black-forest
 
 ![alt text](https://github.com/jonas-kgomo/ArcheryRender/blob/master/okayman.jpg "Logo Title Text 1")


