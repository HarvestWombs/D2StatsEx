#### MainFunc:
- Build - Displays the mouse coordinates on screen (only needed once)
- Static - Nothing special about this one, just draws current info directly on screen
- Popup - If mouse hovers over defined area, then it draws information

#### SubFunc:
- String - Yup it's a string all right. Takes the following parameters
	- StringID
	- Font
	- StringColor (calc)
	- StringLeft
	- StringRight
	- StringY
	- Anchor (Left, Center, Right)

-  Value - Yup it's a value all right. Takes the following parameters
	- StatID
	- StatCalc (if used, StatID is ignored)
	- Font
	- StringColor (calc)
	- StringLeft
	- StringRight
	- StringY
	- Anchor (Left, Center, Right)

- Box - Draws some boxes. Takes the following parameters
	- BoxLeft
	- BoxRight
	- BoxTop
	- BoxBottom
	- BoxStyle (Stroke, Gold, or blank for standard black)
	- BorderColor (Used for Stroke (red,blue,green,alpha), Ex: (100,200,0,255)

- Image - Draws custom dc6 frames. Takes the following parameters
	- GFXFile (Dc6 filename located in "data/global/ui/panel/D2StatsEx/")
	- GFXFrame (Easter Egg hidden here)
	- Drawmode (See appendix)