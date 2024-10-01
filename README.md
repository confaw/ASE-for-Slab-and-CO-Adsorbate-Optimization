Included in this repository are python codes which make use of the package ASE (atomic simulation environment). The codes allow the user to generate slabs of FCC Copper (Cu(111)). 
We can make slabs of any dimension in a unit cell (I made mine as a 4x4x5 slab), and then lock certain layers in place for subsequent DFT optimization calculations using VASP.
I'm interested in observing the CO binding energy as if it were an electrochemical system, so in my case I locked the bottom two most layers of the slab and allowed the top 3 to move.
There are also other files included which show how to place the adsorbate in different positions (Top, Bridge, and Hollow sites).
