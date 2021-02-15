# FrameBuffer Screen
* Author: Yu-Chen Lin 林育辰

## Demo

![](https://github.com/yuchen0515/Computer-Graphics-FrameBuffer-Screen/blob/master/cg-framebuffer.gif?raw=true)

* Using "**FrameBuffer**" to store the "output" and then reflect to a screen box.
* Draw a 3D object with a nice texture mapping via WebGL.
* A point light & cubemap(skybox).

---

## Requirement

### Scene
- [x]  1 point light: you should set a point light and draw a small cube or sphere at its location. (letus be able to see where it is)
- [x]  2 different objects from the external 3D models with nice texture mapping (do not use marioand sonic in the quiz.  Try something new).  You suppose be able to download 3D modelswith nice texture images from clara.io
- [x]  1 ground (e.g. a quad or a big flat cuboid): And, you should put all above 3D objects on thisground correctly.
- [x] Add a background to your scene: using an environment cube map. (You can find some cubemaps by Google ”environment cube map”.  However, you probably have to crop them byyourself.)
- [x] Add a quad as a screen in your scene (let it float on the ground). Choose a fixed camera viewwhich can cover almost all objects in your scene for off-screen rendering and paste the resultfrom the off-screen rendering on the quad. (this is the practice of frame buffer objec

### Illumination
- [x] You should implement a correct and nice-looking local illumination (ambient+difusse+specularand phong shading) for every objects in your scen

### User Interaction
- [x] Users can rotate their view direction by pressing and dragging the mouse.
- [x] Users can move forward or back along the view direction by press ”w” and ”s”, respectively.
