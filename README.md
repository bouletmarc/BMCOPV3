# BMCOP

The BMCOP is a Coil On Plug Project made with Pico2 RP2354 for Honda/Acura running on OBD1 ecus and with a distributor.

# Introduction

The BMCOP need 3x Signal Inputs pins to acheive triggering all the four(4x) Coils (ICM, FC1 Pin3, FC1 Pin4)
The BMCOP can output RPM Signal for the Tachometer

# Editable Parameters and Features

- Wastedspark
- RPM Output Invert
- Long Pulse under 2step
- Desync Time (ticks)
- Firing Order
- Threshold for 'Resync's' Events
- Tach correction (RPM Output)
- Datalogging*
- Error Report (Red Led flashes error codes and datalog can show error code)
- Firmwares can be updated easily
- BMCOP Editor Software

# Installation

- In the ECU, at the FC1 header location, solder the Males pin headers to attach the BMCOP (you need to remove the knock board if present)
- Connect ICM (A21) to the BMCOP
- Connect 12v (A25) to the BMCOP
- Connect the 'RPM Output' signal from the BMCOP to your Tach
  -> On most cars, disconnect the Blue (RPM) wire from the distributor and connect with the BMCOP
  -> On certains 99-00 models, the Blue (RPM) wire is missing on the distributor connector, the Tach wire is connected directly with the ICM wire going out of the ecu. Locate where the two wires connect together, but the Tach(RPM) wire and connect with the BMCOP
- On the Distributor, remove/cut the 12v wire (usually Black/Yellow) so the internal coil inside the distributor isn't powered
- You can use the 12v wire normally powering the distributor to connect with each coils (12v signal)
- Connect each Coils with the appropriate Pins on the BMCOP (Cylinder #1 start on the timing belt side, 4# is by the distributor side)
- Connect each Coils 'Ground' wires

# Usage

The BMCOP is ready to be used upon purchasing it, just insert in the ecu, get the wiring done and start the car!

If you want to edit the Defaults Parameters, you can download and use the BMCOP Editor

![alt tag](https://github.com/bouletmarc/BMCOPV3/blob/main/BMCop Editor/BMCOP_EDITOR.png)


[Clic HERE to Check my others Products!]:<https://bmdevs.fwscheckout.com/>
