# Array Font Header
Some of my collection of font that i already convert to C array hedaer.Mainly use for "immediate gui" like ImGui,egui,nuclear gui and etc.

## How to use ? 
Add the font to your project folder and "#include" the font.

```c++
#include "Ubuntu-Regular.c"

// Call the font using related framework function
// Most common way is to load the font binary at memory
// imgui example :
io.Fonts->AddFontFromMemoryTTF(Ubuntu_Regular, 24, 14px);
```
