This document outlines specifications for the major hardware components

## Example Imaging Ultrasound Hardware Block Diagrams

https://www.analog.com/en/applications/markets/healthcare-pavilion-home/imaging/medical-ultrasound.html

http://www.ti.com/solution/ultrasound-scanner

## Transmit Side
The transmitter excites the ultrasound transducer with high-voltage (order +/- 100 V) waveform. Ideally this is accomplished via, for each channel, a suitable digital to analog converter (DAC) followed by an amplifier with sufficient rails and slew rate. For our initial (Phase I) prototype, we'll use dedicated ultrasound pulser integrated circuits (ICs). These generate what are essentially square waves with user-specified timing. Examples include:

[Microchip HV7321](http://ww1.microchip.com/downloads/en/DeviceDoc/20005639A.pdf)

[Maxim MAX4940A](https://datasheets.maximintegrated.com/en/ds/MAX4940-MAX4940A.pdf)

[ST STHV800](https://www.st.com/resource/en/data_brief/sthv800.pdf)

These often include integrated transmit/receive switches designed for ultrasound signals, simplifying the overall circuit.

## Receive Side

