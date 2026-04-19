![alt text](https://github.com/sallywuzhere/unity-kun/blob/main/project-title.jpg?raw=true)

# Unity-kun: An Open Source Shonen Avatar for Unity
The goal of this project is to offer a masculine alternative to <a href="https://unity-chan.com/">Unity-chan</a>, the wonderful mascot from Unity Japan.

Unity-kun is derived from a VRoid/VRM base, so has a typical skeleton compatible with VRoid animation sets.

Unity-kun has a full set of 52 Apple ARKit Blendshapes as well as the default VRoid Blendshapes; we are using EyeJoints rather than ARKit Blendshapes to move the iris/pupil.


## Installation
In Unity, open **Window → Package Manager → + → Install package from git URL** and paste:

```
https://github.com/sallywuzhere/UnityKun.git?path=Packages/com.sallywuzhere.unitykun
```

Pin a specific version by appending a tag, e.g. `#v1.0.0`.


## Package Contents
- Unity-kun FBX
- Unity-kun Textures and Materials
- Unity-kun Unity Prefab
- VRM MToon shader


## Credits
Blendshapes were copied directly from @hinzka's male model, here: https://github.com/hinzka/52blendshapes-for-VRoid-face

Unity-kun's materials introduce an MToon shader dependency, which is included from UniVRM, here: https://github.com/vrm-c/UniVRM

Unity-kun's textures are based on assets from VRoid Studio modified to match Unity-chan's character design and color palette.


## License
- **Code & project**: MIT (see `LICENSE`)
- **MToon shader**: MIT © VRM Consortium / Masataka SUMI (see `Packages/com.sallywuzhere.unitykun/Shaders/LICENSE.txt`)
- **Textures derived from VRoid Studio presets**: subject to the [VRoid Studio Character Usage Guidelines](https://vroid.com/en/license)
