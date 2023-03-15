This is a preset and set of params to automatically load The Bezel Project MAME overlays as backgrounds.

You will need to verify your image path by opening the "MAME.Slangp" file in a text editor.

### MAME.slangp
```cpp
#reference ":/shaders/shaders_slang/bezel/Mega_Bezel/Presets/Base_CRT_Presets/MBZ__3__STD__GDV.slangp"

#reference "MAME_$CORE-ASPECT-ORIENT$.params"

BackgroundImage = ":/overlays/ArcadeBezels/$GAME$.png"
```

I am using the ```:/``` syntax to point to the default folder. If you aren't running on Windows (e.g. if your overlays folder isn't within your Retroarch folder.) you will need to use a direct or relative path that points to your images.

You will also need to copy the $GAME$.png to your image folder to work as a background for roms that The Bezel Project doesn't have overlays for.

Download the ZIP file, unpack it into your /config/MAME/ folder, copy the PNG to your images folder, and have fun! :-)