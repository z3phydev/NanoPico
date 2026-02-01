## NanoPico
# What is it?
Its a RP2040 Devboard ment for software apllications. It features 16 MB of flash storage and a Male USB A port
# Why did I make it?
I made it because well nothing similar exists, there are many rp2040 devboards but I just couldnt find one that was as small as posible with a male port and no gpio.
# How to use / setup
Once you recive the PCB download the 16mb.uf2 file. Plug it into your pc while shorting the F Pads. Once your PC recognises it you can stop shorting the pads. Then copy 16mb.uf2 to the drive. The drive should now disappear and reappear as "CircutPython". From here you can edit boot as you wish or do other things with python.

# 3D Model

<img width="390" height="748" alt="Screenshot 2026-02-01 151454" src="https://github.com/user-attachments/assets/f9feb7fa-a012-4725-8341-99bcac76e9bc" />
<img width="1121" height="723" alt="Screenshot 2026-02-01 151311" src="https://github.com/user-attachments/assets/5da5d07c-e3fb-4e0f-8009-90e651a400fe" />

# PCB (all layers)

<img width="505" height="659" alt="Screenshot 2026-02-01 152844" src="https://github.com/user-attachments/assets/b96f8237-105c-4464-82b7-33ab200cad66" />
<img width="504" height="641" alt="Screenshot 2026-02-01 152856" src="https://github.com/user-attachments/assets/6fa8be39-9a62-4e38-915a-ad0715be9bea" />
<img width="460" height="589" alt="Screenshot 2026-02-01 152904" src="https://github.com/user-attachments/assets/38aa9c43-046e-4518-8e3b-5951d6af5351" />
<img width="437" height="631" alt="Screenshot 2026-02-01 152910" src="https://github.com/user-attachments/assets/83b905c7-d53b-4b0b-98ec-11fe81a9c1eb" />

# Schematic

<img width="1279" height="966" alt="image (6)" src="https://github.com/user-attachments/assets/087418ab-ac6f-42f1-9ca0-f9cfcc04f8ea" />

# BOM

|Comment            |Designator                                                  |Footprint                        |JLC Part No.|Mft Part No.   |
|-------------------|------------------------------------------------------------|---------------------------------|------------|---------------|
|100nF              |C4, C5, C6, C10, C11, C12, C13, C14, C15, C16, C17, C20, C21|201                              |C49062      |CL03A104KP3NNNC|
|1uF                |C8, C9                                                      |402                              |C14445      |CL05A105KP5NNNC|
|10uF               |C1, C2, C3                                                  |603                              |C19702      |CL10A106KP8NNNC|
|15pF               |C22, C23                                                    |603                              |C1644       |CL10C150JB8NNNC|
|1 kOhm             |R3, R4                                                      |402                              |C11702      |0402WGF1001TCE |
|27 Ohm             |R5, R6                                                      |402                              |C25100      |0402WGF270JTCE |
|47 kOhm            |R7, R8                                                      |402                              |C25563      |0402WGJ0473TCE |
|10 Ohm             |R9                                                          |603                              |C22859      |0603WAF100JT5E |
|Low Voltage Dropout|U3                                                          | SOT-23-5                        |C404027     |TLV75533PDBVR  |GB
|12MHZ Crystal      |Y2                                                          |SMD2520-4P                       |C90603      |Q24FA20H00687  |
|Male USB A         |J2                                                          |USB A Molex 48037-2200 Horizontal|C136453     |480372100      |
|RP2040             |U1                                                          |LQFN-56 (7x7)                    |C2040       |RP2040         |
|16MB Flash Storage |U2                                                          |SOIC-8-208mil                    |C97521      |W25Q128JVSIQ   |

## Total Price if using PCBWAY with assembly should come to around 45 GBP (60 USD)
