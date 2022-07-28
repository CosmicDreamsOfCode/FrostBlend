![[Pasted image 20220728222942.png]]
## SWBF2 Markings Var.1
Used for meshes using the shader `SS_CharactersPreset_CloneTrooperMarkings`

---
## Inputs

- **Base Colour**
	- The base colour of the material.
- **Marking Colour 1,2**
	- Colours of markings.
- **Marking Mask 1,2**
	- Mask inputs for markings.
- **Smoothness**
	- The smoothness of the material.
- **Smoothness Gamma Correction**
	- Sets the gamma value of the smoothness value. Primarily used to correct non-colour smoothness inputs to SRGB. 0 for off, 1 for on.
- **Reflectance**
	- How reflective the material is.
- **Reflectance Gamma Correction**
	- Sets the gamma value of the Reflectance value. 0 for off, 1 for on.
- **AOSL**
	- AOSL texture input.
- **Colour AO Strength**
	- Sets the strength of the AO on the colour.
- **Reflection AO Strength**
	- Sets the strength of the AO on the reflectance.
- **NM**
	- NM texture input.
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
