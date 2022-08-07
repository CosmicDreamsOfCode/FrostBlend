![[Pasted image 20220807194649.png]]
## Frostbite Hair
Standard hair shader.

---
## Inputs

- **Base Colour**
	- The base colour of the material.
- **Alpha**
	- Alpha transparency.
- **Smoothness**
	- The smoothness of the material.
- **Smoothness Gamma Correction**
	- Sets the gamma value of the smoothness value. Primarily used to correct non-colour smoothness inputs to SRGB. 0 for off, 1 for on.
- **Reflectance**
	- How reflective the material is.
- **Reflectance Gamma Correction**
	- Sets the gamma value of the Reflectance value. 0 for off, 1 for on.
- **Normal X, Y**
	- Sets the X and Y values of the materials normals. If no input is avilable leave at 0.5 on both or shading will break.
- **Metalness**
	- Makes the material more or less metallic in appearance.
- **Reflectance Metalness Addition**
	- Set to 1 to add Metalness on top of the Reflectance.(Mainly for internal use, don't reccomend touching)
- **Metalness Gamma Correction**
	- Sets the gamma value of the Metalness value. 0 for off, 1 for on.
- **Normal Strength**
	- The strength of the normals.
- **Hair Strength**
	- Sets the strength of the hair/transmission effect. Higher values will make the colour darker but will increase the amount of light able to pass through it. Reccomended value is 0.5.