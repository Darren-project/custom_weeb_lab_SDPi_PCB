# PCB for Weeb Lab's SDPi

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
<img width="744" height="761" alt="image" src="https://github.com/user-attachments/assets/101ff0e2-578e-47e1-a332-b7057c847085" />

PCB top view
<img width="899" height="812" alt="image" src="https://github.com/user-attachments/assets/335b3ead-279a-47d0-82cd-d211d724c4b6" />

Schematics
<img width="1526" height="821" alt="image" src="https://github.com/user-attachments/assets/d8131eba-2876-43cc-ab44-be0e92923197" />

