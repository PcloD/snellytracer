
# Snelly

[Snelly](http://snelly.net) is a webGL [dispersion](https://en.wikipedia.org/wiki/Dispersion_(optics)) visualization (inspired by [Tantalum](https://benedikt-bitterli.me/tantalum/)). 

A large number of light rays are cast into a transparent object from a laser, and drawn to the framebuffer. The resulting normalized image converges to a visualization (actually a volume rendering) of the "fluence" (i.e. energy density) of the light in the scene. 

  - Scenes are specified by a signed distance field, where regions with negative signed distance lie in the interior of the refracting material, assumed homogeneous. Thanks to [Shadertoy](https://www.shadertoy.com/) it is easy to create lots of interesting scenes this way.
	
  - A number of physically correct dielectric models are provided, obtained from [refractiveindex.info](http://refractiveindex.info/)
	
  - The emitter is a laser pointer with adjustable radius and spread. The emitted light spectrum is specifiable as either a flat band, a monochromatic line, or blackbody radiation at a specified temperature.

Controls
========

  - left-click and drag to rotate view
  - right-click and drag to pan
  - right-click on surface to target emitter on hit point (right-click off surface to clear target)
  - H to toggle GUI
  - F11 to toggle fullscreen



---

![alt tag](https://raw.githubusercontent.com/portsmouth/snellytracer/master/images/gem.png)
![alt tag](https://raw.githubusercontent.com/portsmouth/snellytracer/master/images/fibre2.png)
![alt tag](https://raw.githubusercontent.com/portsmouth/snellytracer/master/images/glass.png)
![alt tag](https://raw.githubusercontent.com/portsmouth/snellytracer/master/images/knot.png)
![alt tag](https://raw.githubusercontent.com/portsmouth/snellytracer/master/images/slabs.png)
![alt tag](https://raw.githubusercontent.com/portsmouth/snellytracer/master/images/menger.png)