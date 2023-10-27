# drkhrse 1:1 RGB30 Bezels
My 1:1 aspect ratio 720p portable system bezels for Retroarch. Currently a WIP with more setup instructions added later.

Originally created for the RGB30.

Open game and then go to the [Quick Menu](https://github.com/OnionUI/Onion/wiki/Global-Shortcuts) for Retroarch (Select + X buttons) > On-Screen Overlay > Overlay Preset > Choose cfg file. Save the override on the content folder or per game basis.

For offset bezels
Settings->
- Video->
  - Scaling->
	- Integer Scale: OFF
	- Aspect Ratio: Custom
	- Width :640
	- Height:576

- Gameboy Pocket - GBP_int_offset.cfg
	- X position:40
	- Y Position:41
			
	- Video Filter: Dot_Matrix_4x_GB_Pocket_Grid
	- Core Options > Internal Palette > GB - Pocket
		
- Gameboy Light - GBL_int_offset.cfg
	- X position:40
	- Y Position:41
			
	- Video Filter: Dot_Matrix_4x_GB_Light_Grid
	- Core Options > Internal Palette > GB - Light

- Gameboy Color - GBC_int_offset.cfg
	- X position:40
	- Y Position:41
		
- Gameboy DMG - GB_DMG_int_offset.cfg
	- X position:40
	- Y Position:60
   
	- Video Filter: Dot_Matrix_4x_GB_DMG_Grid
	- Core Options > Internal Palette > GB - DMG
