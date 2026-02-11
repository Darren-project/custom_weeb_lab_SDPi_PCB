# PCB for Weeb Lab's SDPi

<img width="810" height="850" alt="image" src="https://github.com/user-attachments/assets/36448936-f479-4669-a2ba-ef7b489e69e3" />

## What does this PCB do
This PCB features a RP2350 that runs Weeb Lab's [DSPi](https://www.audiosciencereview.com/forum/index.php?threads/introducing-dspi-a-powerful-user-friendly-and-open-source-dsp-for-less-than-a-cup-of-coffee.69343/) which takes in USB Audio from the host pc and allows user to create parametric EQs.
<br> I added the correct caps and resistors to the outputs so that it can be connected to a output devices.
<br> Therefore, I also splitted the SPDIF to a decoder that outputs I2S to a dac and 2 opamps to drive a line out or headphones.

## How to use it
Hold the boot button and download the Weeb Lab's DSPi firmware into it.
<br> Launch the companion app and configure the eq.
<br> At last, connect the device to the output of your choice.

BOM: [Link to CSV](https://github.com/Darren-project/custom_weeb_lab_SDPi_PCB/blob/main/production/bom.csv)

PCB Design <br>
<img width="622" height="636" alt="image" src="https://github.com/user-attachments/assets/66b29d48-b108-4904-a3d9-afb647936c23" />

Schematics
<img width="1574" height="734" alt="image" src="https://github.com/user-attachments/assets/785f69fa-31d4-4198-970a-e6d4c6da89b7" />


