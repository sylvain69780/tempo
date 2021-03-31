# SLC Shadertoy Noob notebook

![Noob](Regularnoob.png)

* TOC
{:toc}

## Notes month per month
### Notes of March 2021

| Shader | Comments | Preview |
| -------- | -------- | -------- |
| [LukeRissacher - Museum of random planets](https://www.shadertoy.com/view/XttGzj) | Interested by the colors, noise function and the terrain having terraces. | ![No Preview](https://www.shadertoy.com/media/shaders/XttGzj.jpg) |
| [patu - Wreck Scanners ](https://www.shadertoy.com/view/4tfyzf) | Interest by the artistic work and the DOF effect. Nice to see the Gamma correction effect. | ![No Preview](https://www.shadertoy.com/media/shaders/4tfyzf.jpg) |
| [TekF - Realistic Flag](https://www.shadertoy.com/view/3tcfDf)   | May be very usefull to adapt with a different pattern ! | ![No Preview](https://www.shadertoy.com/media/shaders/3tcfDf.jpg) |
| [munrocket - Fast glow with iteration count](https://www.shadertoy.com/view/3dcXWX)   | I searched a lot time how to make a glow effect. Finally get one from Shaw, this one may help also. | ![No Preview](https://www.shadertoy.com/media/shaders/3dcXWX.jpg) |
| [Friol - The dream of a red paper plane ](https://www.shadertoy.com/view/wsBBDV) | Poetic and generative music. Under rated shader ! | ![No Preview](https://www.shadertoy.com/media/shaders/wsBBDV.jpg) |
| [Shane - Hexagonal Maze Flow ](https://www.shadertoy.com/view/llSyDh) | Many details, many advice, like the "Very basic hatch line effect." | ![No Preview](https://www.shadertoy.com/media/shaders/llSyDh.jpg) |
|[Shane - Cellular Blocks ](https://www.shadertoy.com/view/ltySRt)|Just Awsome|![No Preview](https://www.shadertoy.com/media/shaders/ltySRt.jpg)|
|[stb splitting things](https://www.shadertoy.com/view/XdKSWW) | Illusion of living things ! Only an illusion because in reallity just a reaction diffusion simulation formula. |![No Preview](https://www.shadertoy.com/media/shaders/XdKSWW.jpg)|
| [Kali - Circuits](https://www.shadertoy.com/view/XlX3Rj) | Impressive 2D Fractal | ![No Preview](https://www.shadertoy.com/media/shaders/XlX3Rj.jpg) |

### Notes of February 2021

I want probably make another shader related more to geomery than modelling, especially methods for having more domain repetition methods. There is many topics possibles. Like this [Fibonacci mapping](https://dokumen.tips/reader/f/spherical-fibonacci-mapping-fibonacci-mapping-benjamin-keinert-1matthias-innmann)

| Shader | Comments | Preview |
| -------- | -------- | -------- |
| [Quick Lighting Tech](https://www.shadertoy.com/view/ttGfz1) | Blackle : A gold mine of tricks for a fast ligthing, the [Youtube Video](https://youtu.be/FilPE91ACOA) is great. Discovered his [page](https://suricrasia.online/demoscene/functions/) about live coding GLSL functions. | ![No Preview](https://www.shadertoy.com/media/shaders/ttGfz1.jpg) |
| [Coaster Jungle ](https://www.shadertoy.com/view/tl3fRS) | Good use of domain repetition. | ![No Preview](https://www.shadertoy.com/media/shaders/tl3fRS.jpg) |
| [High-Collar Cubes](https://www.shadertoy.com/view/WldBRH)  | I like the patterns on these cubes, the rendering to good also. | ![No Preview](https://www.shadertoy.com/media/shaders/WldBRH.jpg) |
| [Perfect Pistons Example](https://www.shadertoy.com/view/Wl3fD2) | Blackle Tricks How to make domain repetition without artifacts. Many ideas in the discussion. | ![No Preview](https://www.shadertoy.com/media/shaders/Wl3fD2.jpg) |
| [Alchemical symbols](https://www.shadertoy.com/view/3scyWN) | I like this way to display symbols using SDF | ![No Preview](https://www.shadertoy.com/media/shaders/3scyWN.jpg) |
| [Xyptonjtroz](https://www.shadertoy.com/view/4ts3z2) | Many nice effects from nimitz, noise and dust storm. | ![No Preview](https://www.shadertoy.com/media/shaders/4ts3z2.jpg) |
|[Dry ice 2](https://www.shadertoy.com/view/WlVyRV)|Nice fog simulation|![No Preview](https://www.shadertoy.com/media/shaders/WlVyRV.jpg)|
| [Metallic Tubeworms](https://www.shadertoy.com/view/3ltfzM) | DR2 made it before I do ! | ![No Preview](https://www.shadertoy.com/media/shaders/3ltfzM.jpg) |
| [4D Wild Kifs](https://www.shadertoy.com/view/wttBzM)  | Iapafoto Awsome again | ![No Preview](https://www.shadertoy.com/media/shaders/wttBzM.jpg) |
| [Metaballs: Let's get together](https://www.shadertoy.com/view/4lKXzd) | A lot of tricks on golfing shared in the comments of this simple shader. | ![No Preview](https://www.shadertoy.com/media/shaders/4lKXzd.jpg) |
| [Paint streams](https://www.shadertoy.com/view/WtfyDj) | Shader of the week, awsome fluid simulation.|![No Preview](https://www.shadertoy.com/media/shaders/WtfyDj.jpg)|

### Notes of January 2021

* I may have the idea to create a [syringe](http://t1.gstatic.com/images?q=tbn:ANd9GcQdQBMzk80Wb1Ez37QRUeum5zDsP5JB7YIglZhZnFKrLw5-9Z8zBTHxLtga53eDfrMcGF2YoFmrBYB1_ekUs0c) with 2021 on it instead of the graduation marks.
* I wanted to create an **aminated character**, but the hair modeling is tricky. I leart about Beriez curves, there is an analytical distance fonction for quadratic because they are planar (3 control points), not for cubic (4 control points, the most communly used). I found another approach using arc of circles in [this](https://www.ryanjuckett.com/biarc-interpolation/) paper with C++ code and [this](https://arxiv.org/pdf/1711.00935.pdf) PDF using Mathlab. There about approximating [Spirals](https://www.rug.nl/research/portal/files/14477957/05c5.pdf).
* There is a lot of ideas in [this shader](https://www.shadertoy.com/view/wlj3zV) in the comments about creating "splines" using arc of cirles. The try I'am currently doing with 3 joints main interest many guys, but I have to make it clean. The idea is to provide a length for the total of the join and have 3 numbers to set the proportions of the 3 segments.

| Shader   | Comments | Preview  |
| -------- | -------- | -------- |
|[Simple Bend](https://www.shadertoy.com/view/Wlt3DM)|IQ shows a way to bend the space, I also had a deep look at "Joint 3d" of iapafoto.|![No Preview](https://www.shadertoy.com/media/shaders/Wlt3DM.jpg)|

| Shader   | Comments | Preview  |
| -------- | -------- | -------- |
|[Octopi](https://www.shadertoy.com/view/3tycDW) | A rope function based on spline interpolation that may be very usefull for animation ! |![No Preview](https://www.shadertoy.com/media/shaders/3tycDW.jpg)|
| [Drippy Room](https://www.shadertoy.com/view/MstGWX) | Water effect to study |![No Preview](https://www.shadertoy.com/media/shaders/MstGWX.jpg)|
| [Raymarch template GGX](https://www.shadertoy.com/view/3tyyWm) | A proposal for a template thanks to darkeclipz |![No Preview](https://www.shadertoy.com/media/shaders/3tyyWm.jpg)|
| [Specular highlight models ](https://www.shadertoy.com/view/WtycWW) |At least I will understand how to get a specular ligthing. |![No Preview](https://www.shadertoy.com/media/shaders/WtycWW.jpg)|
|[Marble Marcher: SE](https://www.shadertoy.com/view/3lKyDR) | Playable game ! A big piece of work. |![No Preview](https://www.shadertoy.com/media/shaders/3lKyDR.jpg)|
| [Electric Flower (Music)](https://www.shadertoy.com/view/3lVyD1)|Nice effect for the music. Using buffer feedback effect seems simple. | ![No Preview](https://www.shadertoy.com/media/shaders/3lVyD1.jpg) |
| [Warping - procedural 2](https://www.shadertoy.com/view/lsl3RH)|IQ teaching Deformation of procedural textures as far I understand, to be studied. | ![No Preview](https://www.shadertoy.com/media/shaders/lsl3RH.jpg) |
|[Procedural walk animation](https://www.shadertoy.com/view/WlsSWS)| Procedural animation, very difficult exercice. |![No Preview](https://www.shadertoy.com/media/shaders/WlsSWS.jpg)|
|[SH18 Woman](https://www.shadertoy.com/view/4tdcWS)|Photographic look|![No Preview](https://www.shadertoy.com/media/shaders/4tdcWS.jpg)|
|[Head](https://www.shadertoy.com/view/wlf3WX)|How to model an human head using SDF. |![No Preview](https://www.shadertoy.com/media/shaders/wlf3WX.jpg)|
|[Meditation for dummies](https://www.shadertoy.com/view/Md3GR4)|Head by Iapafoto|![No Preview](https://www.shadertoy.com/media/shaders/Md3GR4.jpg)|
|[Sparks from fire](https://www.shadertoy.com/view/wl2Gzc)| Good fire particle effect |![No Preview](https://www.shadertoy.com/media/shaders/wl2Gzc.jpg)|
| [lots o' particles](https://www.shadertoy.com/view/wl2Gzc) | Making particles in a shader is not simple, this is a try to use multipass but the move of the particles is very limited. | ![No Preview](https://www.shadertoy.com/media/shaders/MdtGDX.jpg) |
| [Buckyball Fracture](https://www.shadertoy.com/view/WlKyzW) | Many be usefull when trying some **explosion effects** | ![No Preview](https://www.shadertoy.com/media/shaders/WlKyzW.jpg) |
| [Ray marching practice 5](https://shadertoy.com/view/4sKBW3) | The **flower** shape seems to me very good, it's not easy to get a petal. | ![No Preview](https://www.shadertoy.com/media/shaders/4sKBW3.jpg) |
| [Danger Noodle ](https://www.shadertoy.com/view/wlVSDK)  | Perfect modelling, the skin and the eyes are incredible, BigWings masterpiece. | ![No Preview](https://www.shadertoy.com/media/shaders/wlVSDK.jpg) |
|[Mandelcloud explorer](https://www.shadertoy.com/view/wttyDX) | I like the fuzzy rendering. And the code seems accessible to me. | ![No Preview](https://www.shadertoy.com/media/shaders/wttyDX.jpg) |
| [Euclidean Honeycombs](https://www.shadertoy.com/view/WsfcRn) | How to tile the 3D space. |![No Preview](https://www.shadertoy.com/media/shaders/WsfcRn.jpg) |
|[Two Tweets](https://www.shadertoy.com/view/MsfGzM)|Found this shader in the IQ playlist, very short like a Tweet,  my understanding is that this is a minimal ray marching algorithm. Try `return length(fract(p)-.5)-0.2; ` to get spheres |![No Preview](https://www.shadertoy.com/media/shaders/MsfGzM.jpg)|
|[Joe Gardner (Soul Pixar)](https://www.shadertoy.com/view/3ltyRB)| This shader show a neat and nice looking approach to compute transparent objects. **usefull to me** |![No Preview](https://www.shadertoy.com/media/shaders/3ltyRB.jpg)|
|[TIE Fighters](https://www.shadertoy.com/view/WlcyD7)|dean_the_coder is not stopping to publish very elaborated SDF modelling, keeping the code short and clear. Many comments too about optimization. Impressive ! |![No Preview](https://www.shadertoy.com/media/shaders/WlcyD7.jpg)|
|[hexastairs: ladder like + doors](https://www.shadertoy.com/view/wsyBDm)|Fabrice gives a neat example of how to make false 3D using hexagons tiles. Inspiring ! One can imagine to make a animated character here. |![No Preview](https://www.shadertoy.com/media/shaders/wsyBDm.jpg)|
|[Marching Die](https://www.shadertoy.com/view/3sVBDd)|Shane publishing a new shader is always an event, like when you just received your favorite magazine.|![No Preview](https://www.shadertoy.com/media/shaders/3sVBDd.jpg)|
|[Planetary gears golfed ( 439 ch)](https://www.shadertoy.com/view/ttdyRs)|Nice logo creation, golfed by Fabrice|![no preview](https://www.shadertoy.com/media/shaders/ttdyRs.jpg)|
|[Caves - WebGLSamples ](https://www.shadertoy.com/view/wsyBWc)|Interactive creation on holes in a terrain|![no preview](https://www.shadertoy.com/media/shaders/wsyBWc.jpg)|

### Notes of December 2020

Studied the shape of the Helix

I had the idea to study the shape of the Helix, there is many examples of it on Shadertoy.
I have an idea seems fun to make a scytale ! https://en.wikipedia.org/wiki/Scytale
These can be found [searching using the helix keyword](https://www.shadertoy.com/results?query=helix&sort=popular&from=24&num=12)

| Shader   | Comments | Preview  |
| -------- | -------- | -------- |
| [Springs of Arbitrary Profile](https://www.shadertoy.com/view/ttB3DV) | **usefull to me** | ![ttB3DV](https://www.shadertoy.com/media/shaders/ttB3DV.jpg) |
| [DNA helix](https://www.shadertoy.com/view/lt33RB) | shader with a lot of usefull functions **usefull to me** | ![lt33RB](https://www.shadertoy.com/media/shaders/lt33RB.jpg) |
| [Infinite stair](https://www.shadertoy.com/view/tdlfWX) | One of Fabrice's many pulishing **inspiring to me** | ![tdlfWX](https://www.shadertoy.com/media/shaders/tdlfWX.jpg) |

### Other shaders and acticles that interested me in December

| Shader   | Comments | Preview  |
| -------- | -------- | -------- |
| [OKLab color space](https://www.shadertoy.com/view/WtccD7)     | **RGB** is not the perfect tool to pick a color based on human perception, **HSV** is widely used instead, and this **OKLab** encoding even seems a better approach for some good reasons. **usefull for me**     | ![WtccD7](https://www.shadertoy.com/media/shaders/WtccD7.jpg)     |
| [Day at the lake](https://www.shadertoy.com/view/wl3czN) | Cloud, water, terrain, **still magical for me**. | ![wl3czN](https://www.shadertoy.com/media/shaders/wl3czN.jpg) |
|[Polyhedron again](https://www.shadertoy.com/view/XlX3zB)|Polyhedrons good reference by **knighty**|![No Preview](https://www.shadertoy.com/media/shaders/XlX3zB.jpg)|
| [Wythoff construction](https://www.shadertoy.com/view/ldXczX) | Contruction of polyhedrons based on reflextions, perfect to be used in a shader. It's based on repeated reflexions regarding 3 plans, not really easy to me to visualize the construction. The numbers refers to the fractions of angles on the triangular tiles and the pipe sign the position of the point to use as vertex to the polyhedra. **interested** | ![ldXczX](https://www.shadertoy.com/media/shaders/ldXczX.jpg)     |
| [AURORA landscape](https://www.shadertoy.com/view/ttScDc) | **still magical for me** | ![ttScDc](https://www.shadertoy.com/media/shaders/ttScDc.jpg) |
| [opensimplex noise](https://www.shadertoy.com/view/tttyRH) | Even if seems there is many other noise functions possible and found on Shadertoy, this one is a "well known" and popular one, there is a **Coding Train** youtube video about it. **usefull to me** | ![tttyRH](https://www.shadertoy.com/media/shaders/tttyRH.jpg) |
| [metaball shader](https://shadertoy.com/view/4sXXWM) | colorfull, don't know how it works yet. **still magical** | Preview not available ?  ![4sXXWM](https://www.shadertoy.com/media/shaders/4sXXWM.jpg) |
| [Clickable Starfield](https://www.shadertoy.com/view/XlcSDr) | I had noticed this Incredible work of iapafoto | ![No Preview](https://www.shadertoy.com/media/shaders/XlcSDr.jpg) |
| [Clickable Starfield](https://www.shadertoy.com/view/ttGyDW) | Reworked by Ollj | ![No Preview](https://www.shadertoy.com/media/shaders/ttGyDW.jpg) |
| [Shaw - WASP Coils](https://www.shadertoy.com/view/WdjSDw) | Here I found at least a clear way of how to make an easy **glow effect** : Shaw and helix **usefull to me** | ![No Preview](https://www.shadertoy.com/media/shaders/WdjSDw.jpg) |
| [Satisfaction Machine](https://www.shadertoy.com/view/tdGfDy) | Great idea, Helix **usefull to me** | ![No Preview](https://www.shadertoy.com/media/shaders/tdGfDy.jpg) |
| [Modeling of the bridge, and boat](https://www.shadertoy.com/view/Xd3fWr) | fast and accurate using spheres and cylinder intersect | ![No Preview](https://www.shadertoy.com/media/shaders/Xd3fWr.jpg) |
| [Flame shader](https://www.shadertoy.com/view/WsccDH) | fast and nice. Theory behind to read also. IQ liked it, it should be good. | ![No Preview](https://www.shadertoy.com/media/shaders/WsccDH.jpg) | 
| [Snow is falling](https://www.shadertoy.com/view/4lfcz4) | Snow falling from tholzer good effect | ![No Preview](https://www.shadertoy.com/media/shaders/4lfcz4.jpg) |
| [Miracle Snowflakes](https://www.shadertoy.com/view/Xsd3zf) | There is a music sound shader in this one. | ![No Preview](https://www.shadertoy.com/media/shaders/Xsd3zf.jpg) |
|[Sphere and Cable](https://www.shadertoy.com/view/wlKXWc) | A ball in a torus made of cables, well animated and rendered. Notable equation for cables reaction. Fabrice made a golfed version of it. | ![No Preview](https://www.shadertoy.com/media/shaders/wlKXWc.jpg) |
|[Christmas 2016 orbs](https://www.shadertoy.com/view/ltcSzs) | Many light sources, interested me | ![No Preview](https://www.shadertoy.com/media/shaders/ltcSzs.jpg) |
|[Rosace 3d](https://www.shadertoy.com/view/ldcSzB)| Oh nooo ! Fabrice short rosace with textures. Seems a variant of the twister trick. |![No Preview](https://www.shadertoy.com/media/shaders/ldcSzB.jpg)|
|[Polar Grid Motion](https://www.shadertoy.com/view/XtcfRH) | Shane again ! |![No Preview](https://www.shadertoy.com/media/shaders/XtcfRH.jpg)|
| [Magic Particles Multi-Pass](https://www.shadertoy.com/view/ld3GWS) | How to add magic sparks |![No Preview](https://www.shadertoy.com/media/shaders/ld3GWS.jpg)|
| [Magic Sparks](https://www.shadertoy.com/view/Xs33R2) | Nice |![No Preview](https://www.shadertoy.com/media/shaders/Xs33R2.jpg)|
| [GPU Bossa (sound)](https://www.shadertoy.com/view/tdyfRy) | Very relaxing sound  | ![No Preview](https://www.shadertoy.com/media/shaders/tdyfRy.jpg) |
| [The Shining](https://www.shadertoy.com/view/3stBDf) | It is nice to see short AND readable programs, very usefull style, but too bloody for me ! The preview is black. | ![No Preview](https://www.shadertoy.com/media/shaders/3stBDf.jpg) |

### Notes of November 2020

| Shader   | Comments | Preview  |
| -------- | -------- | -------- |
|[Several types of stella](https://www.shadertoy.com/view/WsyfWh)|To be studied |![No Preview](https://www.shadertoy.com/media/shaders/WsyfWh.jpg)|

| Shader   | Comments | Preview  |
| -------- | -------- | -------- |
|[TRuck Driving](https://www.shadertoy.com/view/wsGBDh)|Very fun ! |![No Preview](https://www.shadertoy.com/media/shaders/wsGBDh.jpg)|
|[(not) moving circle illusion](https://www.shadertoy.com/view/tdyfRR)|Fun illusion !|![No Preview](https://www.shadertoy.com/media/shaders/tdyfRR.jpg)|
|[Fabrice's utilities](https://www.shadertoy.com/view/llySRh)||![No Preview](https://www.shadertoy.com/media/shaders/llySRh.jpg)|
|[Joint 3D from iapafoto](https://www.shadertoy.com/view/tdyBDh)|very usefull for modelling. I wonder if there is a problem with the sign function that becomes zero and causes some artifacts at some instants (difficult to capture). |![No Preview](https://www.shadertoy.com/media/shaders/tdyBDh.jpg)|
|[impulse_glass](https://www.shadertoy.com/view/lttBzN)|Refractions|![No Preview](https://www.shadertoy.com/media/shaders/lttBzN.jpg)|
|[Whack-A-Mole Pistons](https://www.shadertoy.com/view/WtXcWB)| I copied the Mettalic effect. [Video explanation from Blackle]( https://www.twitch.tv/videos/590616102) and [fake ibl tdhooper](https://www.shadertoy.com/view/tlscDB) |![No Preview](https://www.shadertoy.com/media/shaders/WtXcWB.jpg)|
|[Arrows](https://www.shadertoy.com/view/MlGSRR)|Re usable patterns|![No Preview](https://www.shadertoy.com/media/shaders/MlGSRR.jpg)|
|[Interactive fluid with caustics](https://www.shadertoy.com/view/ttdXRf)|[Fluid simulation](http://developer.download.nvidia.com/GTC/SIGGRAPH_Asia_2011/PDF/WaterSim_Chentanez.pdf) Seems the height **fluid** simulation of my nephew Cyrille|![No Preview](https://www.shadertoy.com/media/shaders/ttdXRf.jpg)|
|[Spiral patterns](https://www.shadertoy.com/view/4ljBWd)|I copied this one to do my Helix shader procedural texture.|![No Preview](https://www.shadertoy.com/media/shaders/4ljBWd.jpg)|
|[Golfed](https://www.shadertoy.com/view/MtjfDG)|Golfed version.|![No Preview](https://www.shadertoy.com/media/shaders/MtjfDG.jpg)|
|[Human Meat Grinder ](https://www.shadertoy.com/view/Ws3Bzf)|This shader uses a dedicated shade function , good idea to keep|![No Preview](https://www.shadertoy.com/media/shaders/Ws3Bzf.jpg)| 
|[Selfie girl](https://www.shadertoy.com/view/WsSBzh)|IQ published Hoody (renamed Selfie girl) and it's just mind blowing. There is a youtube video about how it's modelled and enlightened ! |![No Preview](https://www.shadertoy.com/media/shaders/WsSBzh.jpg)|

I wanted to do a domain repetition using a **spiral**, also wanted to make a distance "for comments" shader. This led to my Christmas shader.
[Spiral equations](http://benice-equation.blogspot.com/search/label/Spiral)
I saw 3 types of spirals
* Log spirals as used by IQ to create a snail.
* Archimedian spirals that I used because there is a constant spacing between spires.
* Double center spirals that are just built on arc of circles. 

| Shader   | Comments | Preview  |
| -------- | -------- | -------- |
| [a Cube in a spiral](https://www.shadertoy.com/view/wdGfzD) ||![No Preview](https://www.shadertoy.com/media/shaders/wdGfzD.jpg)|
| [Spiral with N branches](https://www.shadertoy.com/view/4ldyWN) ||![No Preview](https://www.shadertoy.com/media/shaders/4ldyWN.jpg)|
| [Fabrice helix here](https://www.shadertoy.com/view/lsdfD8) ||![No Preview](https://www.shadertoy.com/media/shaders/lsdfD8.jpg)|
| [This spiral with UV is used](https://www.shadertoy.com/view/Mdd3R7) ||![No Preview](https://www.shadertoy.com/media/shaders/Mdd3R7.jpg)|
| [Nyarchimedes Spiral ](https://www.shadertoy.com/view/lsS3WV) |**usefull to me** to create my Christmas shader. |![No Preview](https://www.shadertoy.com/media/shaders/lsS3WV.jpg)|
| [wet ink britney](https://www.shadertoy.com/view/4l33zN) |Again UV on an archimedian spiral|![No Preview](https://www.shadertoy.com/media/shaders/4l33zN.jpg)|
| [Fabrice Short spiral](https://www.shadertoy.com/view/wls3W4) ||![No Preview](https://www.shadertoy.com/media/shaders/wls3W4.jpg)|
| Nice https://www.shadertoy.com/view/4tdczl ||![No Preview](https://www.shadertoy.com/media/shaders/4tdczl.jpg)|
| [Logpolar domain repetition]( https://www.shadertoy.com/view/wdsSWs) ||![No Preview](https://www.shadertoy.com/media/shaders/wdsSWs.jpg)|
| Very cool particle system with rendering [Folosh Demosplash 2020](https://www.shadertoy.com/view/wstBzf)||![No Preview](https://www.shadertoy.com/media/shaders/wstBzf.jpg)|
|https://www.shadertoy.com/view/Xtlyzl| Seems there is a challenge to make very short shaders using the apollonian 3D fractal, this is totally crazy |![No Preview](https://www.shadertoy.com/media/shaders/Xtlyzl.jpg)|
|[Fast edge detection](https://www.shadertoy.com/view/4s2XRd)|is very nice for cartoon like shading.|![No Preview](https://www.shadertoy.com/media/shaders/4s2XRd.jpg)|
|I love also [Jungle Gym](https://www.shadertoy.com/view/tsjfRw) cartoon like shading. ||![No Preview](https://www.shadertoy.com/media/shaders/tsjfRw.jpg)|
|This one https://www.shadertoy.com/view/WsyfzR is using the webcam to onboad us in the flying saucer, and there is a very nice glow effect to rip. This is using a closeness out variable in the ray marching procedure.||![No Preview](https://www.shadertoy.com/media/shaders/WsyfzR.jpg)|
|https://www.shadertoy.com/view/Xtl3zf |I have to learn about texutes that is a full domain of knowledge and may start by this one from IQ about to create non repetitive textures|![No Preview](https://www.shadertoy.com/media/shaders/Xtl3zf.jpg)|
|https://www.shadertoy.com/view/llySRh |I never really understood how to make a good use of the font texture, but this shader from Fabrice may help |![No Preview](https://www.shadertoy.com/media/shaders/llySRh.jpg)| 
|https://www.shadertoy.com/view/Wd3BWj |Usage of the font texture|![No Preview](https://www.shadertoy.com/media/shaders/Wd3BWj.jpg)|
|https://www.shadertoy.com/view/XsjBWW |the is also this great one short|![No Preview](https://www.shadertoy.com/media/shaders/XsjBWW.jpg)|
|https://www.shadertoy.com/view/lt2SDc |A large number of metaballs to simulate cell division |![No Preview](https://www.shadertoy.com/media/shaders/lt2SDc.jpg)|
|https://www.shadertoy.com/view/Ws3fR7|A simple effect Ocean effect|![No Preview](https://www.shadertoy.com/media/shaders/Ws3fR7.jpg)|
|https://www.shadertoy.com/view/ts3fDs|A very short Twister shader|![No Preview](https://www.shadertoy.com/media/shaders/ts3fDs.jpg)|
|[3D Cellular Tiling](https://www.shadertoy.com/view/ld3Szs)| Shane is source of inspiration and astonishment, I should go to have a deep look at it.|![No Preview](https://www.shadertoy.com/media/shaders/ld3Szs.jpg)|
|https://www.shadertoy.com/view/lsfcRB |Noticed nice Torus based shaders of balkhan Kaiman, this one has a blackbody color function|![No Preview](https://www.shadertoy.com/media/shaders/lsfcRB.jpg)|
|[Snaliens](https://www.shadertoy.com/view/tlV3zy) |This very nice shader of the day is simple but colorfull and using simple 2d primitives with blending. Note for myself : I have to be cute to be liked, because I'am not technically impressive !|![No Preview](https://www.shadertoy.com/media/shaders/tlV3zy.jpg)|
|[over the moon](https://www.shadertoy.com/view/4s33zf)|There is also the Bigwings tutorials [other the moon](https://www.youtube.com/watch?v=LLZPnh_LK8c) about blending and 2d effects.|![No Preview](https://www.shadertoy.com/media/shaders/4s33zf.jpg)|
|[Torus Pipes](https://shadertoy.com/view/wlj3zV)|by iq. shows how to make a jonction of capped torus to make a long pipe. Here there is 32 capped torus, this is impacting the frame rate. I see now obvious way to improve by boxing, the calculations are already quite cheap. Will not be fluid on mobile, but good on PC.|![No Preview](https://www.shadertoy.com/media/shaders/wlj3zV.jpg)|
|[Dancing Tentacle](https://shadertoy.com/view/XldSDn)|by mplanck. A very fun tentacle with Inverse Kinematic|![No Preview](https://www.shadertoy.com/media/shaders/XldSDn.jpg)|
|https://www.shadertoy.com/view/XtSyzh|Cubic truchet is very nice and there is a lot of examples in Shadertoy, even a good explanation here. This shader uses also the keyboard with memory of key pressed ! Usefull. |![No Preview](https://www.shadertoy.com/media/shaders/XtSyzh.jpg)|
|https://www.shadertoy.com/view/4lfcRl|One among many Shane examples, **greatly commented with lot of tricks !** I like the little Windows blinking.|![No Preview](https://www.shadertoy.com/media/shaders/4lfcRl.jpg)|
|https://www.shadertoy.com/view/MtSyRz|This one managed to implement a flow in the truchet 3d pattern|![No Preview](https://www.shadertoy.com/media/shaders/MtSyRz.jpg)|

Fabrice's explanation of keyboard input and other features [here](https://shadertoyunofficial.wordpress.com/2016/07/20/special-shadertoy-features/)

care should be done about textures borders and Mip Mapping. 
Seems this need to be managed to avoid artifacts.
Don't know for the moment how to do it.

### Notes of October 2020

| Shader   | Comments | Preview  |
| -------- | -------- | -------- |
|[Fab31 #inktober2020 "crawl" ](https://www.shadertoy.com/view/3d3fRr)|During Inktober, Fabrice made a crawling worm.|![No Preview](https://www.shadertoy.com/media/shaders/3d3fRr.jpg)|
|https://shadertoy.com/view/WldGWM|this may be a good exercice to make it with joins as described by IQ here|![No Preview](https://www.shadertoy.com/media/shaders/WldGWM.jpg)|
|https://www.shadertoy.com/view/3tKGDW |What is missing is the function to get the position matrix for the next segment of the joint. This in done in 3D by PixelPhil in a function named joint3DMatrix|![No Preview](https://www.shadertoy.com/media/shaders/3tKGDW.jpg)|
|https://www.shadertoy.com/view/3ld3DM|this in not in the IQ example for joints, Would probably have to make it from my own.|![No Preview](https://www.shadertoy.com/media/shaders/3ld3DM.jpg)|
|https://www.shadertoy.com/view/XtSczy|There is also inverse kinematik approach like in|![No Preview](https://www.shadertoy.com/media/shaders/XtSczy.jpg)|
|https://shadertoy.com/view/XldSDn|very nice|![No Preview](https://www.shadertoy.com/media/shaders/XldSDn.jpg)|
|https://www.shadertoy.com/view/Xtf3Rj|This one |![No Preview](https://www.shadertoy.com/media/shaders/Xtf3Rj.jpg)|

## General thoughs and advices about Shadertoy
### How I "Discovered" Shadertoy

| Shader | Comments | Preview |
| -------- | -------- | -------- |
| [IQ - Happy Jumping](https://www.shadertoy.com/view/3lsSzf) | Inigo impressive near 6 hour tutorial "LIVE Coding and Painting with Maths" | ![No Preview](https://www.shadertoy.com/media/shaders/3lsSzf.jpg) |

In March 2020, the COVID made me having more time to search about creative coding.


And in fact I discovered more than I expected !
* This site started from the very generous idea of **"Create and Share your best shaders with the world and find Inspiration"**. It's a place to watch small pieces of **GLSL** code generating awesome images. 
* I (re)discovered the **demoscene** and their community very active on Shadertoy.
* I **discovered** with Shadertoy **the ray marching** algorithm that allows to build real time realistic 3D scenes "without any Maya or Blender or something", just your keyboard, some calculations on a paper sheet and knownlege of how to make a "for" loop. 
* I discovered Computer Graphic professionals, working for the Cinema or for the Video Game industry or greats scientists working in LABs in image and video processing.
* In fact I discovered a full domain I had no idea of.


I should say that is was a BIG shock for me to discover the power of the fragment shaders, procedural rendering and the massive parallelism of the moderm graphic cards. I was crazy about it.
The last time I made real time graphics was while programming the Motorola 68000 at 8Mhz of my ATARI 520 ST, trying to draw some pixels on the 320x200 16 colors screen, with 512 KB of RAM. 
It was like jumping in a time machine for me to discover that shaders uses now high precision floats instead of integers, that fragment shaders runs using GPU massive parallelism, buffers and memory are not a problem, all is 1 million time faster !
And you can do it online with few lines of code in your browser with Shadertoy !

What is special with Shadertoy is the **community**, animated by IQ and other big contributors. They are present on the site to comment the newly  published shaders, and it's really cool. 
The facebook and Twitter community is also very active. There is a Discord server.
The technical limitations introduced by the GLSL language also avoid to have a too large creations. 
For example building a complete game is very painfull and a true challenge. 
For this, the published shaders are mainly simple, few line of code, centered on procedurals technics, performance tricks aesthetic and colors.
The **ergonomy** of the site is also great, with Alt+ENTER shortcut to compile in a second and see the results, making possible to spend hours making a step by step improvements to your art work until to reach the perfection !

### What you can do on Shadertoy


**Generative art** is all what Shadertoy is about. I think this video explains quite well what it is.
[Tim Holman - Generative Art Speedrun](https://www.youtube.com/watch?v=4Se0_w0ISYk)

As this Three.js [page](https://threejsfundamentals.org/threejs/lessons/threejs-shadertoy.html) explains very well, you will not here develop a full 3D application, but short GLSL programs for fun or to experiment and learn about 3D rendering technics.

I can see shaders in the following main categories (personal point of view)
* Masterpieces
    * Here the creator tries to sum of many different technics in the same shader. Need weeks of work. The creator wants to prove and show his artistic and technical skills.
* Nice Illustrations of functions and algorithms
    * Tutorial, here the creator wants to make a visualisation of what he learnt and wants to communicate, like construction of polyhedrons or the rendering of clouds.
* Reproduction
    * The author tries to reproduce a picture, or a scene of a movie for example, for the pleasure.
* Golfing
    * Making very short program, the pleasure is to find how its works with so few characters !
* VJing (Video Jockey) 
    * Some shaders like spychedelic fractals may be used during "parties".
* Results of live coding parties. 
    * Memorize some formulas and retype them quickly, you will impress your audience.
* Playable games and emulators
    * No idea how they can even do it !
* Optical illusions 
    * Fun ! But be prepared for headhatches if you look at it too long.

### Is there better alternatives to Shadertoy ?

I like the community of Shadertoy, so even if more featured sites may exist, there is no better place for me today than Shadertoy to post a shader !

Below alternative sites I noticed

* https://smoothstep.io/
    * Allow to make animations, ready to use templates available. Focus on animation.
* https://www.vertexshaderart.com/
    * To learn about verted Shaders in GLSL, the sound texture offers a lot of possibilities.


### Is this notebook usefull ?
The idea of this notebook is to references some usefull information I found in the shaders of Shadertoy.
Hopefully this also may help someone to make cool things on this web site.

There is about 50 000 shaders published, and the code is accessible but seems like magic stuffs if you don't know the theory behind. My idea is to reference the ones that I studied in details or just noticed for later.
I think that you don't need to be an senior programmer in order to start with shadertoy. The proof is that I'am not working as a developer currenlty. It's far simplier to learn GLSL than to learn to play Piano for example (I tried).

This may be a great initiation for young programmers, the same way I did my firt programs on my ATARI 520 ST. 
But in order to really get fun, you should interested in maths, problems, aesthetic in curves, nature and science in general. This is at least my opinion.
You need also to learn some mathematical basis teached in engeneer's preparation schools.
You should be also sensible to short programming and **performance optimization**. It's more programming for **physicians** than for business software engeneers. For this, **you should be informed about the underlying hardware architecture**. (the GPU)

### Learn about fragment shader in the GPU
Here I have to put some usefull links that explains how your programm is executed in parallel for each single pixel on the screen.
This is very important to understand the theory before coding anything or you will fall in big performance issues.
* Technical explanation in details ! [How GPU works](http://www.cs.cmu.edu/afs/cs/academic/class/15462-f12/www/lec_slides/462_gpus.pdf)
* [thebookofshaders](https://thebookofshaders.com/01/?lan=fr)
* [the graphics codex](http://graphicscodex.com/)
To start learning about the rendering equation and physically based rendering.
then, dive into [PBRT](http://www.pbr-book.org/)
### Building Worlds With Two Triangles
It is a quite curious idea to say that we will use only 2 triangles to create worlds. 

In fact this is a nice way to explain that **we will not use all the complex vertex (meshes processing) layers** of the rendering pipeline but only draw two triangles forming a rectangle covering the whole screen.
All the program logic is in the fragment shader that shades the pixels of these triangles ! 

This seems totally crazy to me because these programs should be executed for every pixed on screen, they should be very optimized and compact. The ray marching algorithm is perfect for this. Let's read what Inigo is writing in this presentation, we can easylly imagine attendees getting stucked by the surprise.

[Rendering Worlds With Two Triangles](https://www.iquilezles.org/www/material/nvscene2008/rwwtt.pdf)
### Tips and tricks
How to start to create your first shaders ?


In fact it's simple, all the links to start about shaders are at the bottom of [Shadertoy's main page](https://www.shadertoy.com/) ! 
* After going the shadertoy page bottom links, you may go here : 
* Inigo page [2D distance functions](https://www.iquilezles.org/www/articles/distfunctions2d/distfunctions2d.htm)
* [3D distance functions](https://www.iquilezles.org/www/articles/distfunctions/distfunctions.htm) 
* Like IQ pages, a lot of usefull functions by **MERCURY** group, a gold mine. A lot of functions like polyhedrons and domain repetition functions
    * http://mercury.sexy/hg_sdf/
    * [port on Shadertoy](https://www.shadertoy.com/view/Xs3GRB)
* To look at
    * MathUtils.frag of Syntopia's Fragmentarium
        * https://github.com/Syntopia/Fragmentarium/blob/master/Fragmentarium-Source/Examples/Include/MathUtils.frag
* Fabrice N, some links among many : 
    * Generate colors using short [Hue function](https://www.shadertoy.com/view/ll2cDc)
    * Catalog of tools code [iResolution, iMouse, iDate, etc](https://www.shadertoy.com/view/llySRh)
    * Catalog of widgets [digits/sliders/kbd widgets - 2](https://www.shadertoy.com/view/MdKGRw)
    * [Desmos graphes](http://evasion.imag.fr/~Fabrice.Neyret/demos/DesmosGraph/indexImages.html) 
    * https://desmosgraphunofficial.wordpress.com/
* Fold space and build some Fractals (The Kaleidoscopic IFS fractals)
    * http://blog.hvidtfeldts.net/index.php/2011/08/distance-estimated-3d-fractals-iii-folding-space/
* Cineshader template : [CineShader Lava](https://www.shadertoy.com/view/3sySRK) 
* Font texture explanation :
    * https://www.shadertoy.com/view/llcXRl (by creator)
    * https://www.shadertoy.com/view/4sBfRd
### Why computer graphics artists are magicians ?
* There is for me a true analogy with "magicians", in the way we are giving the best illusion to our brain that there is something real on the screen. It is very funny to trick our perceptions of shapes and colors.
### Tutorials and raymaching templates
* Inigo Quilez
    * https://www.youtube.com/c/InigoQuilez/about
    * Starter shader : [here](https://www.shadertoy.com/view/ldfSWs)
    * Catalog of [3D SDF](https://www.shadertoy.com/view/Xds3zN)
* Art of Code
    * https://www.youtube.com/c/TheArtofCodeIsCool/about
        * Noise values 
        * [Ray marching starting point](https://shadertoy.com/view/WtGXDD) 
* Demofox blog
    * https://blog.demofox.org/

### Notes about IQ video "Happy Jumping"

"LIVE Coding and Painting with Maths" is a gold mine. There is so much information in this near 6 hours long video that I try here to put here links to interesting parts.


[Work on Candy on the floor, domain repetition, colors, position shift to not align them on a grid](https://youtu.be/Cfe5UQ-1L9Q?t=12892)

[Floor movement like a trampoline](https://youtu.be/Cfe5UQ-1L9Q?t=13183)

[Camera shaking, care to motion sickness !](https://youtu.be/Cfe5UQ-1L9Q?t=13644)

[Let's do some clouds quickly (with sin waves)](https://youtu.be/Cfe5UQ-1L9Q?t=13887)

[Calculated Occusion, adjustment of key, fill, bounce lights intensity and colors, specular](https://youtu.be/Cfe5UQ-1L9Q?t=14387)

The sun_spe ligthing term, very special, is explained at [4:09](https://youtu.be/Cfe5UQ-1L9Q?t=14952) and it is very short. I searched for it for long time.



[fresnel](https://youtu.be/Cfe5UQ-1L9Q?t=15270)

[Soft shadows](https://youtu.be/Cfe5UQ-1L9Q?t=15513)

[Bounding volume](https://youtu.be/Cfe5UQ-1L9Q?t=20158)

### Notes about Shadertoy contributors

Mainly the spirit of Shadertoy is closely related to the **demoscene**. Looking at Wikipedia you will have a good explanation of what it is. 

In resume, these guys are triying to make cool things with their computers. 

I follow some smart guys on Shadertoy. 
Below my naive "groupie" comments about them !


| Login | Comments | URL |
| -------- | -------- | -------- |
| IQ | God (co)Creator of Shadertoy. His exact SDF catalog is a reference used extensively. Resume [impressive](https://www.iquilezles.org/personal/curri/curri.htm). | [Web site](https://www.iquilezles.org/)  [Youtube](https://www.youtube.com/channel/UCdmAhiG8HQDlz8uyekw4ENw) |
| BigWIngs | Canada, These videos are Art works and are showning how to make art work with Maths. | [Youtube](https://www.youtube.com/channel/UCcAlTqd9zID6aNX3TzwxJXg) |
| P_Malin | GB, Paul Malin is a magician, able to make improbable things like a Teletex or Windows 95 GUI in a shader. I also had a look at his blog, creating short (280 char) programs to be executed by a [Tweeter bot !](https://blog.mousefingers.com/post/bbc/bbc_bbcmicrobot/) Here the editor to play with it [Microbot editor](https://bbcmic.ro/) . Paul ! Stop playing with this bot and please come back to Shadertoy !| [blog](https://blog.mousefingers.com/) |
| Shane | Australian, Fantastic creator, creations always nice to watch, code easy to read and commented extensively, he's the Shakespeare of Shadertoy. |[web](http://Rhomboid.com) [Shadertoy](https://www.shadertoy.com/user/Shane)|
| FabriceNeyret2 | French (Grenoble, near Lyon where I live) spends a lot of time posting kind comments and tutos. A lot of advice to take ! |[web](http://evasion.imag.fr/~Fabrice.Neyret/demos/Shadertoy/) [Shadertoy](https://www.shadertoy.com/user/FabriceNeyret2)|

## My creations
### My motivations

Making shaders is like cooking, we try to impress and make me happy and also people watching at it. This is my first motivation.

### I am and will still be an hobbyist !

* I'am able to create a ray marching shader (based on BigWings template)
    * Modelling with SDF
    * Simple lightning
    * Basic textures
* I'am able to create 2D shaders
* I know how to make a transparent objet using multiple rendering pass.
* Have to experiment with noise.
* Have to learn about fluid simulations
* Have to learn about volumetric clouds
* Have to learn about terrain rendering
* Have to learn about cell shading
* To be continued.


### My published shaders

I don't publish all my creations and experiments, I only set a shader public when I think it's presentable and can be inspiring, I think this is what everyone is doing, this avoids to have too much public shaders to browse on Shadertoy. 

In general, I also try to gives instructions to have different fun results by a simple modification of a line of code. **This is a toy** ! 

Many times, friends ask me **how many time** it took to me to make these shaders.
I can tell between 10 to 20 hours of cumulated work in general to get a presentable result for the community and publish it. 
First have the idea and want to share it, work on the message associated to your creation, and good animation, limited artifacts, colors etc. 
As IQ repeat in these videos, **you just need to fix ugly things**, and this needs a lot of time for a newbie, but it's realy pleasant. And the more you learn, the more you are able to see ugly things to fix.

By inverse order of creation time.

| Shader | Comments | Preview |
| -------- | -------- | -------- |
| [Bee Waggle Dance](https://www.shadertoy.com/view/ssX3W2) | I started by trying to replicate the map of my dinner room that has some bee pattern on it, and this ended with this. | ![No Preview](https://www.shadertoy.com/media/shaders/ssX3W2.jpg) |
| [Egg Hunt](https://www.shadertoy.com/view/ttyfDV) | Very quickly done with the new template of BigWings plus domain repetition and fun result ! I think the humain brain is wired to catch Eggs. | ![No Preview](https://www.shadertoy.com/media/shaders/ttyfDV.jpg) |
| [Heart Ribbon](https://www.shadertoy.com/view/wtdBzl) | The Helicoid shape is far more complicated than I expected, obviously because with the difference of the Archimedian spiral, it's a 3D space figure. | ![No Preview](https://www.shadertoy.com/media/shaders/wtdBzl.jpg) |
| [Waiting for two injections](https://www.shadertoy.com/view/3tGcDR) | On this one I played with the 3D fonts and the transparent effect. There is also a more serious message, of hope for 2021. But I'am not here to propagate any political message. | ![No Preview](https://www.shadertoy.com/media/shaders/3tGcDR.jpg) |
|[Happy New Year using a Scytale !](https://www.shadertoy.com/view/3tdczX)| My creation after searching for HELIX functions. | ![No Preview](https://www.shadertoy.com/media/shaders/3tdczX.jpg) |
|[Decorated Christmas Spiral](https://www.shadertoy.com/view/3dVfDc)| After searching for archimedian spiral functions. Fun to see that many comments were about the twisted cylinders wrapped around the spiral, much simplier to get. | ![No Preview](https://www.shadertoy.com/media/shaders/3dVfDc.jpg) |
|[Kawaii Looper Caterpillar](https://www.shadertoy.com/view/WdcfDs)| After studying IQ's joint functions based on a set of capped torus, and BigWings 2D shaders technics (smiley face youtube tutorials). I had fun testing the results of diffrents procedural patterns from Shane, I spent also many time to work on the amination. ** * |![No Preview](https://www.shadertoy.com/media/shaders/WdcfDs.jpg)|
|[Rocket planet](https://www.shadertoy.com/view/wdVyDR) | After searching for some polyhedron functions in order to compute only 1 rocket. |![No Preview](https://www.shadertoy.com/media/shaders/wdVyDR.jpg)|
|[Walking donuts](https://www.shadertoy.com/view/tscfzs)  | After working on polar repetition. **tuto**|![No Preview](https://www.shadertoy.com/media/shaders/tscfzs.jpg)|
|[Roundabout symetry](https://www.shadertoy.com/view/ts3yzB)  |**tuto** polar repetition, I think this transformation is missing the the IQ page about distance functions. But this is mentioned in one of his video tutorial. |![No Preview](https://www.shadertoy.com/media/shaders/ts3yzB.jpg)|
|[Rocket Toy](https://www.shadertoy.com/view/3dSBRG)|***Was very happy with this one***. I modelled the rocket for the first time with IQ's SDFs, without even understanding how the ligthing is working. Added a BigWings tutorial starfield background. Tried also a glow effect. Newbies can dare all. |![No Preview](https://www.shadertoy.com/media/shaders/3dSBRG.jpg)|
|[SDF for Moss's Egg - for comment](https://www.shadertoy.com/view/wsBBR3) |I'am so proud, this stupid function of mine (total newbie) is mentioned on the IQ page about 2D distance functions (of course, optimized by IQ) ! This pushed me to study more distance functions, on spirals, helix ... |![No Preview](https://www.shadertoy.com/media/shaders/wsBBR3.jpg)|

## Begin in April 2020
### Starting with P5.js
All started with the **Coding Train** and David Shiftman's tutorials. 
The P5.js online editor is great for starting some animations an you can make cools things easyly. 
The subject I used are my son's school drawings about emotions. I scanned and underlined using Inkscape to get an SVG format image. 
Later I was able to add a fire effect shader for the backgroud thanks to shadertoy contributors.
https://editor.p5js.org/sylvain69780/sketches/zzg14OI9i
https://editor.p5js.org/sylvain69780/sketches/SYOoiwzKX
Below another site where you can share your programs but not so much animated. 
I pulished one that was using the fire shader, but unfortunately get no feedbacks from the community. 
The web site is also a too confusing, I love the simple interface of Shadertoy.
https://www.openprocessing.org/

