# lowpricetag-connect

ARM Cortex JTAG/SWD compression connector. Intended as an open source alternative to Tag Connect.

### PCB
See gEDA file DC01.pcb in folder DC01 associated subfolders. Boards can be ordered directly from [OSH Park](https://oshpark.com/shared_projects/uAXMI0N7).

### BOM
- J1: Amphenol 20021511-00010T4LF
- J2: Samtec SIBF-05-F-S-AD
- J3: Samtec SIBF-05-F-S-AB

### Target
Mates with 2x5 1.27mm pitch rectangular pads compatible with Samtex FTSH-105-01-L-DV-007-K, but longer by around 0.5 mm and with guide holes that fit the alignment pins on the Samtec SIBF-05-F-S-AD.

### Usage
The board is compatible with ARM Cortex JTAG/SWD debuggers, such as the Segger J-Link Mini, using a cable that attaches to a 10-pin 1.27 mm pitch IDC socket.For speedy programming, the connector can simply be pressed to the target pad. Mounting holes allow the PCB to be fixed to a clip for a more solid connection while debugging.

