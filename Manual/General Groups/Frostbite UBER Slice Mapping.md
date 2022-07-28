![[Pasted image 20220728222800.png]]
## Frostbite UBER Slice Mapping
Generic FB shader with support for a slice mask and detail maps.

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
- **Slice**
	- Input for a slice texture.
- **Slice Samples 1,2,3**
	- Inputs for slice values. Only the green channel is used here for easy use with AOSL textures.
- **Detail 1,2,3**
	- Texture inputs for detail map tiling textures. Leave at 0.5,0.5,0 if no input.
- **Detail Normal Intensity 1,2,3**
	- Sets the strength of the normals added to the base normals by detail textures.
- **Detail Smoothness Intensity 1,2,3**
	- Sets the strength of the smoothness added to the base smoothness by detail textures.

## Outputs 

- **Shader**
	- Shader output.
- **Mask 1, 2, 3**
	- View filtered slice masks that use the slice sample to preview where detail maps will go.