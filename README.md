# Documentation of Photocurrent Sampling Amplifier
## Daniel Hipp, TU Graz 2024
This document contains a detailed description of how to build and use a transimpedance amplifier that is specifically tuned to the task of photocurrent sampling. A more concise description containing the minimum information to build and operate the device is contained in ‘Quick Guide PCS PCB_en.pdf’.
More information on the design process is available in the bachelor thesis ‘Photocurrent Sampling in free Air’ by Daniel Hipp. Files mentioned within the document are available in the repository [XX].

Content:
1. PCB Layout	2
2. Gain Settings	2
   - First Stage	2
   - Second Stage	3
3. Power Supply Settings	4
   - PS1	4
   - PS2	4
4. Bias Settings	5
5. Grounding	5
   - Ohne Charge Pump (SP2):	5
   - Mit Charge Pump:	6
6. Ein- und Ausgänge: Ratings	6
Eingänge / Ausgänge von links nach rechts:	6
Ratings:	6
Bauteilempfehlungen	7
Jumper Netze	8
Reinigung	8
Versionsidentifikation	8
Bestückung	9
ToDo:	9
![grafik](https://github.com/user-attachments/assets/9bd4391b-f61f-48bb-a2c0-a7f8aa16fee4)

Above is the simple image, below the aligned version
<p align="center">
  <img src="https://github.com/user-attachments/assets/9bd4391b-f61f-48bb-a2c0-a7f8aa16fee4" width="600">
  <br>
  Fig. 1, Inputs and Outputs on PCB
</p>

test: Latex formel syntax inline $\frac{A}{B\cdot \pi}$ and in display mode: 
```math
x = \frac{R}{C \cdot \pi}
```
