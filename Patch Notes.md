  
**v2.04 Final**
- All calc fields are now using D2COMMON_EvalSkillCalc

**v2.03 Alpha**
- Fixed backwords logic in mouse over for popup functions

**v2.02 Alpha**
- Fixed Inventory stats displaying when Quest panel is open

**v2.01 Alpha**
- Fixes Inventory stats displaying when Waypoints panel is open

**v2.0 Alpha**
- Major Overhaul, tons of refactoring
	- Moved to Main/Sub functions setup
	- Removed tons of columns to make it easier to follow
- Added the many panels to draw over
- StringColor is now a calc column
- Allows having many custom Dc6 files per GFXFile column
- Added class column
- Added Anchor column

**v1.2:**
- ValueColor column now supports calcs. (keep it simple, remember the color values above)

**v1.1:**
- Fixed an issue where Calc's were not saved when not using -txt switch
	- Credits to Necrolis/Szumigajowy/Kinpin for code.
- I had to use the same table loading method as Dreamlands does, so I inserted a custom
check for if you are using Dreamlands, else load the table using NewTxt like normal.
This should prevent any overlap in code.

**v1.0:**
- Added a new column "RiN" (Red if Negative) boolean. Pretty self explanatory.
- Code optimization

**v.03:**
- Added a "Calc" column to allow using standard D2 calcs for displaying a stat value.

**v.02:**
- Allow the ability to display a custom DC6 frame for popups.

**v.01:**
Initial release