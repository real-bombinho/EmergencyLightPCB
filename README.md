# EmergencyLightPCB
contains Fritzing file for emergency light PCB

# Function:
- SELV power supply set to 18V,
- direct supply of LED strip 1 and 2 in series (resulting in 2x9V)
- direct supply of LED strip 3 and 4 in series (resulting in 2x9V)
- Buck converter 1 (CC CV) set to suitable voltage/current to trickle charge NiCD batteries and supply emergency strips 1 & 2, Diode D1 preventing back flow from NiCd batteries
 (14V for 10 cells; 11.2V for 8 cells)
- Buck converter 2 can be left out and J1 bridged or dropped via rectifier diode for 8 cell / 11.2V setup, otherwise Buck 2 drops voltage for emergency LEDs to 9V, the gain in efficiency from down volting outweighs the loss of efficiency from the buck converter, 14V might overheat LEDs and shorten life expectation whilst increasing current flow notably.
- Trickle charge current to be set in accordance to the used batteries, allowing for the emergency light current

Fixing holes and PCB size to accomodate 'Industrial Control Box Enclosure Case Din Rail'

Buck converters used: Mini 360 DC-DC Ultra Small Buck Converter; 5A Lithium Charger CV CC buck
Power supply used: HLG-40H-20A Mean Well LED driver

Possible improvement to use brass standoffs for connecting and securing Buck 1

