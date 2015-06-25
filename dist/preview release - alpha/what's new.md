- 2.2.0:
  - **Major updates**
    - HDR Rendering pipeline. See [demo here]() [julien-moreau](https://github.com/julien-moreau)
  - **Updates**
    - Depth-of-field improvements [PR](https://github.com/BabylonJS/Babylon.js/pull/567) [jahow](https://github.com/jahow)
    - Engine now initialize WebGL with preserveDrawingBuffer = false by default [deltakosh](https://github.com/deltakosh)
    - withEpsilon with a user defined epsilon [PR](https://github.com/BabylonJS/Babylon.js/pull/573) [RaananW](https://github.com/RaananW)
    - Adding onAfterRender function in BABYLON.PostProcess [PR](https://github.com/BabylonJS/Babylon.js/pull/572) [julien-moreau](https://github.com/julien-moreau)
    - Improved shaders optimizer to remove specular code when not needed [deltakosh](https://github.com/deltakosh)    
    - Added some utility functions to Vector2/3/4 [PR](https://github.com/BabylonJS/Babylon.js/pull/578) [jahow](https://github.com/jahow)
    - New rawTexture.update function [robgdl](https://github.com/robgdl)
    - Changes to meshes transform baking and added flipFaces [PR](https://github.com/BabylonJS/Babylon.js/pull/579) [jahow](https://github.com/jahow)
  - **Bug fixes**
    - Fixing bug with rig cameras positioning [deltakosh](https://github.com/deltakosh)
  - **Breaking changes**