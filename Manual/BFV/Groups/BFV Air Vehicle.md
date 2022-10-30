![[Pasted image 20221030194133.png]]

## BFV Air Vehicle
Shader for aircraft in BFV

---
## Inputs

- **NSM Texture**
	- Input for the primary texture.
 - **NSM Alpha**
	- Input for the primary textures alpha channel.
- **Detail Texture**
	- Input for the detail tiling texture.
- **Colour 1, 2, 3, 4, 5, 6, 7**
	- Primary colour inputs, 1 through 6 are masked via SubMaterialIndex.
- **Dirt Colour**
	- Colour of the dirt overlay.
- **Metal Colour**
	- Colour of metallic pieces.
- **Colour # Smoothness Mult**
	- Multiply the smoothness of a specific colour area through this value.
- **Marking Smoothness Mult**
	- Multiply the smoothness of markings through this value.
- **Dirt Smoothness Fac**
	- Strength of the dirt overlay on the smoothness.
- **Detail Smoothness Fac**
	- Strength of the detail overlay on the smoothness.
- **Metal Smoothness**
	- Smoothness value of metallic pieces.
- **Camo Masks**
	- Camo mask texture input. Up to 3 supported through RGB.
- **Camo Colour 1, 2, 3**
	  Colour of the camo layers, applied in numerical order.
- **Marking Colour 1, 2, 3, 4, 5**
	- Colour of markings, can be a full texture or solid colour.
- **Marking Mask 1, 2, 3, 4, 5**
	- Masks for the markings.
- **Grunge Texture**
	- Input for a grunge texture to weather the markings. Will be gamma corrected. (γ2.2)
- **Grunge Brightness**
	- Sets the brightness of the grunge.
- **Grunge Contrast**
	- Sets the contrast of the grunge.
- **Invert Grunge**
	- Inverts the grunge map.
