![[Pasted image 20220728222911.png]]
## SWBF2 Kylo
Used for meshes using the shader `Shaders/Presets/SS_CharactersPreset_WalrusCreature`

---
## Inputs

- **CS Colour**
	- CS texture colour input.
- **CS Alpha**
	- CS texture alpha input.
- **NM**
	- NM texture input.
- **NM Alpha**
	- NM texture alpha input.
- **Smoothness Gamma Correction**
	- Sets the gamma value of the smoothness value. Primarily used to correct non-colour smoothness inputs to SRGB. 0 for off, 1 for on.
- **Reflectance**
	- How reflective the material is.
- **Reflectance Gamma Correction**
	- Sets the gamma value of the Reflectance value. 0 for off, 1 for on.
- **Colour AO Strength**
	- Sets the strength of the AO on the colour.
- **Reflection AO Strength**
	- Sets the strength of the AO on the reflectance.
- **DMS Colour**
	- DMS texture colour input.
- **DMS Alpha**
	- DMS texture alpha input
- **Detail 1,2**
	- Texture inputs for detail map tiling textures. Leave at 0.5,0.5,0 if no input.
- **Detail Normal Intensity 1,2**
	- Sets the strength of the normals added to the base normals by detail textures.
- **Detail Smoothness Intensity 1,2**
	- Sets the strength of the smoothness added to the base smoothness by detail textures.
- **SSS Radius**
	- How far rays of light will travel through the object. This works as an RGB value ie. 1,0,0 will allow only red light to pass through far through the object.

## Outputs 

- **Shader**
	- Shader output.
- **Mask 1, 2**
	- View filtered slice masks that use the slice sample to preview where detail maps will go.
