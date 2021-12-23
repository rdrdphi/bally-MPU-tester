# bally-MPU-tester
Bally MPU tester.
André’s MPU 35 Boot tester is an advanced continuity tester to find faults in locked up bally MPU’s of type _35 and _17

![Image not visible](../master/images/frontend.jpg)


It is made of commodity stuff like: resistors,  dupont wires , arduino mega, and a “led and key” module which can be bought from various sources. 


Functions of the tester:

•	Do  advanced continuity check of (including chip select) of :
o	The mc6800 socket
o	The two pia sockets
o	The mc6810 socket
o	The 5101 socket
o	The U2 eprom  socket
o	The U6 eprom socket

•	Simple logic analyzer function to check the startup via a (time and state with mnemonics ). Sampling rates between 100ns and 300ns.

•	See status of reset.

•	Test correct operation of and clock generation  ϕ2 

•	Test ram chips U7(MC6810), U8 (5101)  U11 , U 10 (6821)

•	Test display interrupt generator (U12)

•	Check various logic gates function:
o	U14, U15, U16,U17,U18, U19

•	Hardware Self-test J5 (check correct wiring of the tester is correct)

•	Check for stuck data bits

