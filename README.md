# Light Probe Intensity Adjustment Tool for Unity3D
A tool that allows you to change the brightness of your light probes in Unity3D. 

### Why?

This can be used for adjusting the brightness of your dynamic objects in the scene. By default, it is not possible to change the brightness of light probes in Unity3D. The reason behind this is because SH coefficients of light probes are generated through PBR principles therefore tweaking it can render incorrect results. However, this can become a problem when you are working with unrealistic, cartoony style graphics and in fact, many users requested this feature on Unity forums. This custom script addresses that issue and attempts to resolve this bottleneck. The script can be further developed if there is enough demand from users.

Note that script is only tested in simple scenarios and may not work in certain cases. Use it at your own risk.

![](https://github.com/kemalakay/lightprobes/blob/master/GIF/adam4.gif)

### How To

1. Drag LightProbeIntensity.cs and .smcrsp files to your project
2. Open Tools > Light Probe Intensity Tool
3. Bake your light probes 
4. Adjust the intensity of light probes


Known Issues:
* Resetting the intensity applies same SH values to all light probes

TO-DO (Feature Requests):
* Using a slider for UI
* Changing the intensity of selected probes (currently the intensity of all probes are overwritten)
* Refactoring of some code 

#### Updates: 
* 14/02/2017 - First version of the light probe adjuster
* 06/02/2017 - Initial commit
