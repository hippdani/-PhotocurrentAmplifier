##Photodiode Amplifier Modification
#TODO
- upload picture / files / BOM
- describe use
- describe the photodiodes

The circuit of the PCSA is also suited to convert the photocurrent of a photodiode with little modifications. 
The modifications are necessary to accomodate the reverse bias voltage that is needed for fast operation of a photodiode.
The high pass filter that blocks out the DC from the bias forms a band pass filter together with the intrinsic low pass 
filter of the transimpedance amplifier.

The high capacity of large are (XUV-) photodiodes limits the achievable bandwidth because stability can not be achieved 
at high frequencies and high gains (Max. gain XX Ohm for Model XY photodiode to achieve 1 MHz -3dB Bandwidth).
Additionally, the large are can act as antenna for stray signals and induce oscillations on its own.
Therefore, proper shielding is required around the photodiode.