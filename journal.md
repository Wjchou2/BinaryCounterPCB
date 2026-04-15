# Tuesday Apr 14 - 85 min
Today I wanted to find an interesting project idea to make. I wanted to make something simple but also somewhat useful and interesting, not just an LED decoration. I looked up IC circuits projects and gained some inspiration. I decided to research the datasheets of the NE555 and CD4040 to make a simple binary counter.

I found that the NE555 can generate pulses so I linked that to a SW_Push and wired the output to the input pin of the CD4040 which counts pulses. I then linked an LED to each output Q pin of the CD4040 in order to show the count in binary! 

I then added another button to the reset pin of the CD4040 to reset count to zero. I had to figure out how to not leave the reset pin floating while also being able to control it using the button. I eventually found the solution: wiring a button and a resistor to GND to keep it low until the button was pressed.

<img width="389" height="225" alt="Screenshot 2026-04-15 at 8 52 14 AM" src="https://github.com/user-attachments/assets/b7773b3e-8f99-46e0-ad5a-3e7ffadade56" />


One major challenged I faced was figuring out how to make the NE555 monostable and only generate pulses when the switch was pressed. I did some research and looked up diagrams online to help me figure out the wiring.

<img width="500" height="932" alt="image" src="https://github.com/user-attachments/assets/6d1c41cc-cb15-4f09-a455-ff4a3533cb86" />


