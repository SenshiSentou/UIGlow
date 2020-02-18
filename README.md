# UIGlow
Default Unity UI shader with HDR color support.

## Usage
Create a material with this shader and apply it to a UI Image. To get an actual glow effect make sure that:

- Your post-processing stack of choice has Bloom enabled.
- Your UI element's canvas is set to `Screen Space - Camera` or `World Space`.
- The camera used to render the canvas is using the post-processing effects.
- The camera used to render the canvas has `Allow HDR` checked.
- Your project's Graphics settings has `Use HDR` checked.
