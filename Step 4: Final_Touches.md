# IMGD5010_FinalProject - Final Product

## Input

Originally, I tried an input method that relied on an input field. The documentation for this is found in the references for p5.js, and it appears like the image below:

<img width="188" height="130" alt="Screenshot 2026-05-04 174741" src="https://github.com/user-attachments/assets/6c516342-8fd4-425b-8648-3dffd3b2a94d" />

This implementation did not synthesize well with shaders, because it required writing a repaint function that was called when the input field was updated. This would not be conducive to using the draw function, which iterates every frame. Thus, I sought out another solution for allowing users to switch which effect they were seeing. The keyPressed() function allowed me to alter a variable's value whenever a certain key is pressed. Thus, I could track the current state and switch it with user input.

## Synthesis

Combining the ability to alter the scene with user input, I established a framework in the draw function for holding all three shader effects. These were if statements that directed the draw function to refer to the code copied from one of the three shaders or display the UI to the user. There are some fun quirks with how the project is coded, resulting in small, fun-to-discover elements when you play around. The modularity of this code and the nature of free-coding and iterating on silly implementations leave this project open to many edits. Future design goals might see the introduction of a lightning effect of sorts, a wind shader, a clear practice for generating rain, and more unique interactions when switching between weather effects.

The full project can be referenced here: https://editor.p5js.org/ELZBH/sketches/FTL8walK8
