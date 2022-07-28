![[Pasted image 20220728222726.png]]

## Frostbite PBR UBER
Generic FB shader.

---
## Inputs

- **Base Colour**
	- The base colour of the material.
 - **Smoothness**
	- The smoothness of the material.
- **Smoothness Gamma Correction**
	- Sets the gamma value of the smoothness value. Primarily used to correct non-colour smoothness inputs to SRGB. 0 for off, 1 for on.
- **Reflectance**
	- How reflective the material is.
- **Reflectance Gamma Correction**
	- Sets the gamma value of the Reflectance value. 0 for off, 1 for on.
- **Emmisive Colour**
	- Sets the emmision colour of the material.
- **Emmision Strength**
	- Controls how bright emmision is.
- **Emmision Mask
	- Masks where Emmission will be.
 - **Emmision Mode
	- 0 for Add, 1 for Mix.
- **Alpha**
	- Alpha transparency.
- **AO**
	- AO texture input.
- **Colour AO Strength**
	- Sets the strength of the AO on the colour.
- **Reflection AO Strength**
	- Sets the strength of the AO on the reflectance.
- **Normal X, Y**
    - Sets the X and Y values of the materials normals. If no input is avilable leave at 0.5 on both or shading will break.
- **Metalness**
    - Makes the material more or less metallic in appearance.
- **Reflectance Metalness Addition**
	- Set to 1 to add Metalness on top of the Reflectance.(Mainly for internal use, don't reccomend touching)