<img width="1280" height="640" alt="Binary Counter" src="https://github.com/user-attachments/assets/c7c98c9f-9716-47d8-b4d8-c3254ad7195b" />

<br>
A Simple Binary counter using NE555 and CD4040 ICs and powered by a USB A receptacle. The Board includes 2 buttons (Increment and Reset) and an array of 4x3 LEDs that can show represent a count up to 4095.
To read the binary number, simply add up all the values of the lit up LEDs, and thats the counter number!


[View KiCad board in KiCanvas](https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FWjchou2%2FBinaryCounterPCB%2Ftree%2Fmain%2Fsrc%2Fkicad)

## Schematic!
<img width="500" height="523" alt="Screenshot 2026-04-24 at 2 27 20 PM" src="https://github.com/user-attachments/assets/b0318d19-bf53-4e05-b77c-a9748501ff1f" />

## PCB!

<img width="500" alt="Screenshot 2026-04-19 at 9 12 12 PM" src="https://github.com/user-attachments/assets/eb3dc2aa-b290-435b-b8b8-76917818b30a" />

## 3d Render!

<img width="500" alt="Screenshot 2026-04-19 at 9 12 21 PM" src="https://github.com/user-attachments/assets/3e12956b-13a4-44e8-b0ff-c6ace20f6aea" />





# Usage
- Soldier all the parts onto the board
- Connect to a power source via the USB A receptacle
- Use the buttons to increment and reset the counter!


# BOM

|Id |Designator                              |Footprint                                       |Quantity|Designation|
|---|----------------------------------------|------------------------------------------------|--------|-----------|
|1  |D11,D9,D1,D5,D8,D7,D2,D3,D6,D4,D10,D12  |LED_D5.0mm                                      |12      |LED        |
|2  |C1                                      |C_Disc_D8.0mm_W5.0mm_P5.00mm                    |1       |10 uF      |
|3  |R1                                      |R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal|1       |100k       |
|4  |J1                                      |USB_A_Molex_67643_Horizontal                    |1       |USB_A      |
|5  |R7,R9,R5,R10,R13,R6,R11,R12,R4,R3,R8,R14|R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal|12      |450Ω       |
|6  |U1                                      |DIP-8_W7.62mm                                   |1       |NE555D     |
|7  |C2                                      |C_Disc_D8.0mm_W5.0mm_P5.00mm                    |1       |0.01 µF    |
|8  |R2,R15                                  |R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal|2       |10k        |
|9  |SW2,SW1                                 |SW_PUSH-12mm                                    |2       |SW_Push    |
|10 |C3                                      |C_Disc_D8.0mm_W5.0mm_P5.00mm                    |1       |0.1 uF     |
|11 |U2                                      |DIP-16_W7.62mm                                  |1       |4040       |
