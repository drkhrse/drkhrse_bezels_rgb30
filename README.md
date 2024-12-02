# drkhrse 1:1 RGB30 Bezels
My 1:1 aspect ratio 720p portable system bezels for Retroarch. Currently a WIP with more systems added later.

Originally created for the Powkiddy RGB30.

![Screenshot](/screenshots/overview.png)

Open game and then go to the [Quick Menu](https://github.com/OnionUI/Onion/wiki/Global-Shortcuts) for Retroarch (Select + X buttons) > On-Screen Overlay > Overlay Preset > Choose cfg file. Save the override on the content folder or per game basis. For more info on setting up the RGB30, I highly recommend the [Retro Game Corps Starter Guide](https://retrogamecorps.com/2023/10/27/powkiddy-rgb30-starter-guide/#Bezels).

## For interger scaling bezels
Settings ->
- Video ->
  - Scaling ->
    - Integer Scale: ON

## For integer scaling with offset bezels
Settings ->
- Video ->
  - Scaling ->
    - Integer Scale: OFF
    - Aspect Ratio: Custom
    - Width: 640 (4x)
    - Height: 576 (4x)

  - Gameboy Pocket - GBP_int_offset_x40_y41.cfg
    - X position: 40 
    - Y Position: 41	
    - Video Filter: Dot_Matrix_4x_GB_Pocket_Grid OR LCD3X shader
    - Core Options > Internal Palette > GB - Pocket
		
  - Gameboy Light - GBL_int_offset_x40_y41.cfg
    - X position: 40
    - Y Position: 41
    - Video Filter: Dot_Matrix_4x_GB_Light_Grid OR LCD3X shader
    - Core Options > Internal Palette > GB - Light

  - Gameboy Color - GBC_int_offset_x40_y41.cfg
    - X position: 40
    - Y Position: 41
    - LCD3X shader
  
  - Gameboy DMG - GB_DMG_int_offset_x40_y60.cfg
    - X position: 40
    - Y Position: 60
    - Video Filter: Dot_Matrix_4x_GB_DMG_Grid OR LCD3X shader
    - Core Options > Internal Palette > GB - DMG

## Auto-rotation on WonderSwan bezels
Quick Menu (while running WonderSwan) ->
- Overrides ->
  - Save Core Overrides
  - Load Core Override ->
    - Write down path to override folder scrolling at the top.

Settings ->
- Input ->
  - RetroPad Binds ->
    - Port 1 Controls ->
    - Rotate screen + active D-Pad: Write down values (eg: "8", "rshift" on ArkOS)

Edit "Beetle WonderSwan.cfg" override and add the following, replacing "8" and "rshift" with inputs found above if needed:
  - input_overlay_next = "rshift"
  - input_overlay_next_btn = "8"
