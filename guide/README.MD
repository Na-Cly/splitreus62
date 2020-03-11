# Build Guide (WIP)

## Steps
The only order of steps that matter are diodes before switches. Other than that it's pretty much up to you. I prefer the order listed below.

_Note: this build guide uses the low profile case that is compatible with pcb mounted switches. A case is in the works for plate mounted switches._

#### Diodes
- through hole diodes can be soldered on top of the pcb, or below. The low profile case requires the diodes be placed on top of the pcb. 
- The black line on the diode will always face the square pad on the pcb.

Make sure to test your diodes before soldering the switches in. If you do not have a multimeter I suggest flashing the pro micros and using a paper clip or wire to short each switch to make sure the diodes are all working.

#### Pro Micro
- There are 2 sets of holes for the pro micro. This design was pulled from the Lily58. This allows for both controllers to face upwards using a reversible PCB. The trade off for this is the holes are smaller than usual and are close to the 2nd set of holes. It's important to make sure that there is no extra solder that is joining them together as you could short your pro micro, or in my case the reset switch to ground and it won't work properly. 

#### Switches
