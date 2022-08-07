![[Pasted image 20220807194704.png]]
## Frostbite RSSSAO/RSSSS
Primarily used for skin materials in DICE games but also Star Wars Squadrons.

---
## Inputs

- **Base Colour**
	- The base colour of the material.
- **RSSAO/RSSSS Switch**
	- Set to 0 to use RSSSAO input, 1 to use RSSSS input.
- **RSSSAO**
	- RSSSAO texture input.
- **RSSSS**
	- RSSSS texture input.
- **Colour AO Strength**
	- Sets the strength of the AO on the colour. _(RSSSAO Only)_
- **Reflection AO Strength**
	- Sets the strength of the AO on the reflectance. _(RSSSAO Only)_
- **Normal X, Y**
    - Sets the X and Y values of the materials normals. If no input is avilable leave at 0.5 on both or shading will break.
 - **Smoothness**
	- The smoothness of the material.
- **Smoothness Gamma Correction**
	- Sets the gamma value of the smoothness value. Primarily used to correct non-colour smoothness inputs to SRGB. 0 for off, 1 for on.
- **Reflectance Gamma Correction**
	- Sets the gamma value of the Reflectance value. 0 for off, 1 for on.
 - **Metalness**
    - Makes the material more or less metallic in appearance.
- **Reflectance Metalness Addition**
	- Set to 1 to add Metalness on top of the Reflectance.(Mainly for internal use, don't reccomend touching)
- **Metalness Gamma Correction**
	- Sets the gamma value of the Metalness value. 0 for off, 1 for on.
- **SSS Radius**
	- How far rays of light will travel through the object. This works as an RGB value ie. 1,0,0 will allow only red light to pass through far through the object.