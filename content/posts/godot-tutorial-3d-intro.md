---
title: "Godot Tutorial 3D Intro"
date: 2020-11-02T21:35:08Z
draft: true
---

It's time to learn some Godot Engine, and I've decided to dive all the way into 3D, because sometimes I don't make good choices.

[Godot's tutorials on working in 3D](https://docs.godotengine.org/en/stable/tutorials/3d/introduction_to_3d.html).

## [01 "Introduction to 3D"](https://docs.godotengine.org/en/stable/tutorials/3d/introduction_to_3d.html)
Spatials are objects with properties: location, euler rotation (relative to the parent node), and scale.

Creating 3D models is not very straightforward nor standardised. Software for that: 'DCCs'. You can import either entire 3D scenes from DCCs or .OBJ files to be put inside MeshInstance nodes for display. You can also generate geometry inside Godot using ArrayMesh and SurfaceTool but it is recommended for use with seldom updated models only due to its performance characteristics. For frequently updated models there is ImmediateGeometry.

The WorldEnvironment node can have a skybox, a background colour, and other post-processing effects. There is a default environment with a sky that can be removed (but usually shouldn't be.)

### the editor

Philosophically, the Godot editor tries to mimic the Blender interface. Thankfully, it functions in the metric system. I am very scared by the fact that that was even an open question.

Select the 3D tab to edit 3D scenes. 'Manipulator Gizmos' are the names given to the arrows that manipulate object locations.

Axes by convention:
- X (red) is sides
- Y (green) is up/down
- Z (blue) is front/back

Centre on an object by selecting it in the menu and pressing `F`.

Snap placement or rotation by holding down `Ctrl` while manipulating.

### the camera

> No matter how many objects are placed in the 3D space, nothing will be displayed unless a Camera is also added to the scene.

Well this is obvious now that you put it like that...

Orthogonal or perspective projections.

The camera is associated with a viewport. There are some complicated rules for which camera takes precedence when multiple are in the same scene tree.

### lights

Godot has a limit of 8 lights per mesh.

## [02 "Using 3D Transforms"](https://docs.godotengine.org/en/stable/tutorials/3d/using_transforms.html)

...

### resources I may want to come back to

- [Vector math tutorial](https://docs.godotengine.org/en/stable/tutorials/math/vector_math.html#doc-vector-math)
-