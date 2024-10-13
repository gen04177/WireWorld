# WireWorld
WireWorld simulation 


## Colors:
**Electron Head (Red):** Represents an active part of the electron in the WireWorld simulation. Moves to the next state on each step.

**Electron Tail (Green):** Represents the trailing part of an electron that follows behind the head. Transitions into a conductor.

**Conductor (Blue):** Conductive cells that can carry electrons. Can turn into an electron head if it receives input from nearby heads.

**Empty (Black):** Represents empty space in the simulation grid where no activity occurs.


## Controls:
**Cross:** Adds an electron at the current cursor position.

**Circle:** Clears all electrons from the simulation.

**DPAD Left:** Decreases the simulation FPS (min 5 FPS).

**DPAD Right:** Increases the simulation FPS (max 60 FPS).

**Left analog stick:** Moves the cursor within the simulation area.

**R1:** Zooms in on the current cursor position.

**L1:** Zooms out from the current cursor position.


## FMI:
https://en.wikipedia.org/wiki/Wireworld

https://github.com/gpuhw/wireworld

## Credits:
- J. Tornblom - SDK.
