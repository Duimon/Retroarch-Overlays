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

