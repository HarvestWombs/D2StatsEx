# Column Descriptions

Name             | Description
-----------------|-----------------
Name             | Just a comment field
HcIDx            | Incremental line value (keep your shit in order)
Enabled          | Hmmmmmm......
Panel            | Choose which panel to display on: Panel names are case sensitive (Inven, Char, Shor, Tree, Ques, Wayp, Cube, Help, Merc)
MainFunc         | Choose which type of function to use (Static, Popup, Build)
SubFunc          | Choose which type of function to use (String, Value, Box, Image)
Condition        | Choose the type of condtion this will appear under (leave blank for none)
---------------- | ----------------
MouseLeft        | 
MouseRight       | 
MouseTop         | Defines mouse position for popups
MouseBottom      |
---------------- | ----------------
StringID         | Gets the string index to display
StatID           | Gets the stat namej you want to display ("Stat" column from ItemStatCost.txt)
StatCalc         | Use a custp, fprmula to display for stats (If calc is used "StatID" column is ignored)
Font             | The font used for the string (See Appendix)
StringColor      | The color used for the string (See Appendix) **Also a calc field**
StringLeft       | 
StringRight      | Defines position to use for the string
StringY          |
Anchor           | Anchors the string position (Left, Center, or Right)
---------------- | ----------------
BoxLeft          | 
BoxRight         | 
BoxTop           | Defines posistions for the popup box 
BoxBottom        | 
BoxStyle         | Which type of border to display (Stroke, Gold, or blank for the standard black box)
BorderColor      | Defines the color to use for Box stroke(red,blue,green,alpha) IE: (100,200,0,255)
GFXFile          | Defines the filename to use for SubFunc::Image, all DC6 files to be placed in (data/global/ui/panel/D2StatsEx)
GFXFrame         | Determines which frame to use for displaying DC6 (Easter Egg hidden here)
DrawMode         | See Appendix for list of draw modes
eol              | End of Line