# Retroarch-Overlays

## Introduction
This project aims to provide users access to the art created for the **HSM Bezel Reflection Shader** on hardware not capable of using the shader.

In addition to the overlays provided, I am also providing the project files in case, for example, you have a favorite bezel you would like to use in place of the one provided.

## Usage

I am assuming you know how to load an overlay in Retroarch. The "retroarch_template.psd" and the "retroarch_template_1080.psd" contain a transparent layer named "screen guide". You can use this layer to determine your game screen coordinates. The existing coordinates are as follows:

**4K**
* Viewport Height = 1853
* Viewport Width = 2461
* Viewport x = 690
* Viewport y = 153

**1080**
* Viewport Height = 927
* Viewport Width = 1231
* Viewport x = 345
* Viewport y = 76

This should get you started. Depending on the shader you use, you may have to tweak things a bit, including screen curvature if using.

