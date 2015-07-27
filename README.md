ShaderToy to Touchdesigner
======
This patch convert the shader code found on the website [shadertoy.com](https://www.shadertoy.com/) and make it usable in Touchdesigner.

Copy the program shader code from the website in the shaderProgram DAT.

## Notice
* Work with 60% of the shadertoy.com available.
* The texture use on shadertoy.com must be reimport in touchdesigner and assign to the input of the glsl TOP.
* Basic uniform like iResolution, iMouse and iGlobalTime are already assign in the uniform section of the glsl TOP, if some shader use other type of uniform, those should be add by hand.
* Audio input don't work


## Bug
* Some shader doesn't compile correctly with raymarching and textureCube, feel free to experiement and look if a solution is available or if this is a Touchdesigner limitation of the sampler type.


## Contact
#### creation exnihilo
email: sebastieng@creationexnihilo.com

 

