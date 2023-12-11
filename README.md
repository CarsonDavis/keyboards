# keyboards
In construction place to store keyboard designs
 
## KiCad Tips
### Rotation
If want to draw nice, straight traces, we will want to match the rotation setting to our splays. In my case, I have choosen splays which are multiples of 3, so I will set the rotate to 3

Preferences -> PCB Editor -> Editing Options -> Step for rotate commands

Now, when we are editing, we will press control a to select our board, then r or shift r to rotate. Then x to go back to trace mode.

## Grid Size
For better grid snapping while tracing, you can change the grid size to be smaller. It is located along the top bar of the screen.

## Generating Cases
npx @jscad/cli@1 output/cases/bottom.jscad -of stla -o bottom.stl
