
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED

▪ Link-B Kit with power supply. 
▪ Patch chords. 
▪ 20MHz Dual Channel Oscilloscope. 
▪ 1 MHz Function Generator. 
▪ 1 Meter Fiber Cable. 
---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE
Refer to the block diagram & carry out the following connections and settings. 
▪ Connect the power supply with proper polarity to the kit link-B and switch it on. 
▪ Keep all Switch Faults in OFF position. 
▪ Keep switch SW8 towards TX position. 
▪ Keep switch SW9 towards TX1 position. 
▪ Keep Jumper JP5 towards +12V position. 
▪ Keep Jumpers JP6, JP9, JP10 shorted. 
▪ Keep Jumper JP8 towards sine position. 
▪ Keep Intensity control pot P2 towards minimum position. 
▪ Feed about 2Vpp sinusoidal signal of 1 KHz from the function generator to the IN post of Analog  Connect the output post OUT of Analog Buffer to the post TX IN of Transmitter. 
▪ Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. 
Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by 
screwing it back. 
▪ Connect the other end of the Fiber to detector SFH350V (Photo Transistor Detector) very 
carefully. 
▪ Observe the detected signal at post ANALOG OUT on oscilloscope. Adjust Intensity control pot 
P2 Optical Power control potentiometer so that you receive signal of 2Vpp amplitude. 
Buffer.o measure the analog bandwidths of the phototransistor vary the input signal frequency and 
observe the detected signal at various frequencies. 
▪ Plot the detected signal against applied signal frequency and from the plot determine the 3dB 
down frequency. 
▪ Keep switch SW9 towards TX2 position. 
▪ Keep Jumper JP7 towards +12V position. 
▪ Remove fiber cable from SFH756V (660nm) and slightly unscrew the cap of SFH450V 
(950nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one 
meter fiber into the cap. Now tighten the cap by screwing it back. 
▪ Observe the detected signal at post ANALOG OUT on oscilloscope. 

---

## BLOCK DIAGRAM


<img width="1189" height="704" alt="514753236-1a50e68b-d082-44d3-87f2-1488bbf5f464" src="https://github.com/user-attachments/assets/239a2b23-f4e8-4966-b07f-d43b86ccde48" />



## TABULATION  
**Transmission through Analog Link**

![20251117_164037](https://github.com/user-attachments/assets/0bd9cb47-4e2b-4141-baa3-9f087448233f)




## MODEL GRAPH


![20251117_164141](https://github.com/user-attachments/assets/e9f709d3-90d0-48c9-856a-c4a2de069961)


## RESULT
Thus, the frequency response of the analog fiber optic link was successfully studied, and the bandwidth was determined to be 95 kHz.
