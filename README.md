# Retroarch-Overlays

## Introduction
This project aims to provide users access to the art created for the **HSM Bezel Reflection Shader** on hardware not capable of using the shader.

In addition to the overlays provided, I am also providing the project files in case, for example, you have a favorite bezel you would like to use in place of the one provided.

## Usage

I am assuming you know how to load an overlay in Retroarch. The "retroarch_template.psd" and the "retroarch_template_1080.psd" contain a transparent layer named "screen guide". (Most individual source PSD's have this layer, for templates that don't have the transparent guide there is an "inner shadow/screen guide" layer) You can use these layers to determine your game screen coordinates. The existing coordinates for CRT systems are as follows:

**4K**
* Viewport Height = 1853
* Viewport Width = 2461
* Viewport x = 690
* Viewport y = 153

**4K No Curvature**
* Viewport Height = 2044
* Viewport Width = 2688
* Viewport x = 576
* Viewport y = 58
 
**4K No Curvature Vertical**
* Viewport Height = 2042
* Viewport Width = 1547
* Viewport x = 1147
* Viewport y = 59

**4K Widescreen**
* Viewport Height = 1847
* Viewport Width = 3193
* Viewport x = 323
* Viewport y = 156

**1080**
* Viewport Height = 927
* Viewport Width = 1231
* Viewport x = 345
* Viewport y = 76

**1080 No Curvature**
* Viewport Height = 1022
* Viewport Width = 1344
* Viewport x = 288
* Viewport y = 29

**1080 No Curvature Vertical**
* Viewport Height = 1022
* Viewport Width = 774
* Viewport x = 573
* Viewport y = 29

**1080 Widescreen**
* Viewport Height = 924
* Viewport Width = 1597
* Viewport x = 161
* Viewport y = 78

This should get you started. Depending on the shader you use, you may need to tweak things a bit, including screen curvature if using. I personally use CRT-Geom with the Bezel overlays, they also work well with the curvature shader in Batocera.

Although there is some clipping, the "No curvature" overlays work OTB on Android phones.

### LICENSE
*******************
All the assets, including documentation and code, are published under the 'Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)' Creative Commons license.

Extract from ['CC BY-NC-SA 4.0' Commons Deed](#https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en):


> You are free to:
> - Share &#8212; copy and redistribute the material in any medium or format
> - Adapt &#8212; remix, transform, and build upon the material
> 
> The licensor cannot revoke these freedoms as long as you follow the license terms.
> 
> Under the following terms:
>
> - Attribution &#8212;You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
> - NonCommercial &#8212; You may not use the material for commercial purposes.
> - ShareAlike &#8212; If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
> - No additional restrictions &#8212; You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

For further reading check the ['CC BY-NC-SA 4.0' legal code](#https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en).


  
### REVISION CLAUSE
***************************
The author may at any time revise these Terms and Conditions by updating this documentary.
You are bound by the most current Terms and Conditions every time you visit this repository, or any of the author's related websites, therefore you should periodically review these Terms and Conditions to which you are bound.

