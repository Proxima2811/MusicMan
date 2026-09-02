## Distortion pedal : 
Parts list: 1 2N3904 Transistor, 1 4.7Mohm resistor, 1 220ohm resistor, 2 1N4148 diodes, 1 50k trimpot, 2 47nf film capacitors, 2 TS jacks. Experiment with different parts and values! It's a very flexible circuit.
<img width="1300" height="660" alt="image" src="https://github.com/user-attachments/assets/5f02c44b-e817-418f-90e5-f1d802283270" />

This is a basic diode clipping stage on Falstad.
As you can see, on the right, the signal waveform of the AC signal source is given and on the left, the clipped waveform of Vout is given

### Clipping with a gain stage : 
<img width="1003" height="862" alt="image" src="https://github.com/user-attachments/assets/920d4cde-ad12-47c9-9977-78976784a641" />

## Components and their function

| Component | Function |
|---|---|
| **9V Supply** | Provides DC power to the circuit. |
| **100nF Input Capacitor** | Blocks DC and allows the AC guitar signal to enter the gain stage. |
| **2N3904 BJT** | Gain stage; converts small base-signal changes into larger collector-current changes. |
| **47kΩ Collector Resistor** | Converts changes in collector current into changes in collector voltage. |
| **2.2MΩ Feedback Resistor** | Provides collector-to-base feedback to establish and stabilize the transistor's DC bias. |
| **820Ω Emitter Resistor** | Stabilizes the transistor's operating point through negative feedback. |
| **120nF Output Capacitor** | Blocks the collector's DC bias and passes the amplified AC signal to the clipping stage. |
| **1N4148 & 1N34A Diodes** | Clip the positive and negative signal peaks, creating harmonics and distortion. |
| **A100K Potentiometer** | Controls the output/volume level of the distorted signal. |
| **Ground** | Provides the 0V reference and completes the circuit. |

### Signal Path

**Guitar → Input Capacitor → BJT Gain Stage → Output Capacitor → Diode Clipping → Volume Pot → Output**

## tube screamer

<img width="563" height="450" alt="image" src="https://github.com/user-attachments/assets/a8b743e1-50f1-4f8e-8453-cbbcacfa6cb3" />
<img width="534" height="763" alt="image" src="https://github.com/user-attachments/assets/57daf866-16c0-4805-a2d2-65971ac77000" />
