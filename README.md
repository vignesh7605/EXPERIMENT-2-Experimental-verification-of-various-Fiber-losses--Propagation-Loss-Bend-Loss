# EXPERIMENT-2-OPTICAL-COMMUNICATION
## 🔍 EX.NO: 2 – Verification of Fiber Losses

**Aim:**  
To measure propagation and bending losses for two wavelengths in plastic fiber.

**Equipments Required:**  
- Link-B Kit  
- Patch chords  
- Oscilloscope  
- Function Generator  
- Fiber cables 

**Theory:**  

- Optical Fibers are available in different variety of materials. These materials are usually selected by taking into account their absorption characteristics for different wavelengths of light. In case of Optical Fiber, since the signal is transmitted in the form of light which is completely different in nature as that of electrons, one has to consider the interaction of matter the radiation to study the losses in fiber.

- Losses are introduced in fiber due to various reasons. As light propagates from one end of Fiber to another end, part of it is absorbed in the material exhibiting absorption loss. Also part of the light is reflected back or in some other directions from the impurity particles present in the material contributing to the loss of the signal at the other end of the Fiber. In general terms it is know as propagation loss. Plastic Fibers have higher loss of the order of 180 dB/Km.
Whenever the condition for angel of incidence of the incident lights is violated the losses are introduced due to refraction of light. This occurs when fiber is subjected to bending. Lower the radius of curvature more is the loss. Other losses are due to the coupling of Fiber at LED and photo detector ends.
 

**Procedure:**  
- Connect the power supply with proper polarity to the kit link-B and switch it on.
- Keep all Switch Faults in OFF position.
- Keep switch SW8 towards TX position.
- Keep switch SW9 towards TX1 position.
-	Keep Jumper JP5 towards +12V position.
-	Keep Jumpers JP6, JP9, JP10 shorted.
-	Keep Jumper JP8 towards sine position.
-	Keep Intensity control pot P2 towards minimum position.
-	Feed about 2Vpp sinusoidal signal of 1 KHz from the function generator to the IN post of Analog Buffer.

<img width="743" height="301" alt="image" src="https://github.com/user-attachments/assets/e72fbc49-0624-4b15-a4d4-65f39f04196d" />


-	Connect the output post OUT of Analog Buffer to the post TX IN of Transmitter.
-	Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
-	Connect the other end of the Fiber to detector SFH350V (Photo Transistor Detector) very carefully.
-	Observe the detected signal at post ANALOG OUT on oscilloscope. Adjust Intensity control pot P2 Optical Power control potentiometer so that you receive signal of 2Vpp amplitude.

<img width="716" height="294" alt="image" src="https://github.com/user-attachments/assets/72fea700-a99c-41ed-9dfa-e3bb04be70d8" />


-	Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.
-	Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.
 
 <img width="696" height="286" alt="image" src="https://github.com/user-attachments/assets/01ee210d-f880-4ee7-b18f-95b9a5679aed" />



-	If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ]

Where
a = nepers/ Meter
L1 = Fiber Length for V1 L2 = Fiber Length for V2 This a is for peak wavelength of 660nm
-	Keep switch SW9 towards TX2 position.
-	Keep Jumper JP7 towards +12V position.
-	Remove fiber cable from SFH756V (660nm) & SFH350V and insert one meter fiber between SFH450V (950nm) & SFH350V.
-	Observe the detected signal at post ANALOG OUT on oscilloscope.

<img width="829" height="342" alt="image" src="https://github.com/user-attachments/assets/0ac9a0a2-7c28-4a01-9ffd-ff0f907fac57" />


-	Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.
-	Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.
-	If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ]
Where
a = nepers/ Meter
L1 = Fiber Length for V1 ; L2 = Fiber Length for V2 This a is for peak wavelength of 950nm
-	Compare the two a values.
 
MEASUREMENT OF BENDING LOSSES:
-	Remove fiber cable from SFH450V (950nm) & SFH350V and insert one meter fiber between SFH756V (660nm) & SFH350V.
-	Bend the Fiber in a loop. Measure the amplitude of the received signal.
-	Keep reducing the diameter of bend to about 2 cm & take corresponding out voltage readings. (Do not reduce loop diameter less than 1 cm).
-	Plot a graph of the received signal amplitude versus the loop diameter.

 



**Tabulation:**

![WhatsApp Image 2025-11-17 at 21 34 29_4d5eee30](https://github.com/user-attachments/assets/a6db934f-77e9-4cd0-a20b-5a2170b0bdaa)


**Result:**  
Attenuation and bending loss characteristics verified.


