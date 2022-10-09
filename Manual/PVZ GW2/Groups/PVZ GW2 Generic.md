![[Pasted image 20221009032420.png]]
## PVZ GW2 Generic
Generic shader for GW2.

---
## Inputs

- **Base Colour**
	- The base colour of the material.
- **Alpha**
	- Alpha transparency.
 - **Tint Colour**
	- Tints the base colour.
- **ETT**
	- ETT texture input.
- **ASM**
	- ASM texture input.
- **Normal**
	- Normal texture input.
- **Edge Tint Colour**
	- Tints the edge glow.
- **Edge Exponent**
	- Sets the exponent of the edge glow mask.
- **Edge Emission Strength**
	- Sets the strength of the edge glow emission.
- **Detail Map**
	- Detail map texture input.
- **Detail Strength**
    - Sets the strength of the detail overlay.
- **Emmisive Colour**
	- Sets the emmision colour of the material.
- **Emmision Strength**
	- Controls how bright emmision is.
 - **Emmision Mode
	- 0 for Add, 1 for Mix.
- **Colour AO Strength**
	- Sets the strength of the AO on the colour.
- **Reflection AO Strength**
	- Sets the strength of the AO on the reflectance.

## Outputs 

- **Shader**
	- Shader output.
- **Edge Tint Preview**
	- Connect this to the material output instead of the shader output to see only the edge tint. Helps with finding good settings.