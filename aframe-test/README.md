# Memory Gardens Interview

## Objective
1. Your first task is to take the GLB and create a react app with three.js and aframe.
The room/scene should be available in 3D module for exploration and view.
2. The second task is to create and imbed lights and accents via three.js and aframe on top of the design.
You are free to add any components to the room to improve immersibility and overall experience

## Work Done
- Created a React project
- Installed A-Frame
- Found a three.js godray lighting effect example. A derived version of this example has been directly added
to the project under "aframe-test > src > js". However, it is not fully integrated into the A-Frame container.
- Added building model to the three.js file "godray_effect.js"; the generated godrays interact with the model.

## Findings
- Found example code within the three.js GitHub repo that provided an example of how to leverage three.js
to produce godray lighting effects; advanced lighting effects possible with three.js.
- Three.js GTLF loader could not render the texture material of the building.
- Keyboard controls do not work when an A-Frame scene is rendered with three.js controls enabled.

## Future Work / Work Needed
- Proper integration of the three.js godray effect example into the A-Frame container would take more time
than the 4 hours, but possible.
- A-Frame controls omitted temporarily; three.js-provided controls enabled, however. Completing a full integration would re-enable
A-Frame controls.