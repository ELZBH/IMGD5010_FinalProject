# Cloud Shader

To create a cloud shader, I spent a good amount of time testing out Brownian and Perlin noise from the Book of Shaders. These were effective in other platforms, but I figured I could use a similar design to the Sun Shader's code to have a similar design. The original implementation, which was adjusted and implemented in the rain shader, saw one layer of opaque clouds with x-axis transformations. From here, I tested out very bright and translucent clouds, but they didn't evoke the right feeling either. The final design saw a short animation of clouds growing and "moving" across the screen, layered with a 0.98 alpha score to give some translucency where only one shape is, while leaving the stacked clouds to appear like solid objects.

https://github.com/user-attachments/assets/9847cee7-f256-4813-aca9-0185a33c6ce3

The final version of the project can be found here: https://editor.p5js.org/ELZBH/full/l3QJdvnMa
