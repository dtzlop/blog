Camera Settings Overview
Render Type:

Base: This is a standard camera that renders the scene normally. You can also set it to "Overlay" if you want this camera to render on top of another camera.
Projection:

Type: Perspective - Creates a realistic 3D view where objects farther away appear smaller.
Field of View Axis: Vertical - Controls the vertical angle of the camera's view.
Field of View (FOV): 60 - Sets how wide the camera can see. Higher values capture more but can distort the image.
Clipping Planes:
Near: 0.3 - The closest distance the camera will render objects. Anything closer won't be visible.
Far: 1000 - The farthest distance the camera can see.
Physical Camera:

Disabled. This would simulate real-world camera properties like lens and aperture, if enabled.
Rendering Options
Renderer:

Default Renderer (URP-HighFidelity-Renderer): Uses the Universal Render Pipeline for better visuals and performance.
Post Processing:

Disabled: Post-processing effects (like bloom, depth of field) are turned off.
Anti-aliasing:

No Anti-aliasing: Edges might appear jagged because there’s no smoothing applied.
Stop NaNs:

Disabled: Not preventing NaNs (Not a Number) from affecting the render output.
Dithering:

Disabled: Not applying dithering, which reduces color banding.
Render Shadows:

Enabled: Shadows will be rendered, giving the scene more depth.
Priority:

-1: Determines the rendering order when multiple cameras are active. Lower values render first.
Opaque Texture:

Using Pipeline Settings: Follow the settings defined in the Render Pipeline Asset for opaque textures.
Depth Texture:

Using Pipeline Settings: Depth textures (used for effects like fog) follow the render pipeline’s configurations.
Culling Mask:

Everything: The camera will render all layers. You can restrict it to certain layers if needed.
Occlusion Culling:

Enabled: The camera will not render objects that are blocked by other objects, optimizing performance.
Stack
Cameras:
List is Empty: No additional cameras are layered on top of this one.
