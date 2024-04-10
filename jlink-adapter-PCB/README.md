# JLink-adapter PCB

## Background

This is a simple adapter PCB to go between the 20-pin JLink connector and the 10pin SWD connector.  However, it also adds some simple extra features link a Power LED, and a DUT-Power LED.  

## Todos

1. Consider adding some activity LEDs.
1. Fix the KiBot + Github integration.

## History

V1: First iteration.  Found 1 critical bug where the JLink pinout was flipped.  Also some usability issues were found.
V2: Fixed jlink flipped bug.  Changed to 4 layer board.  Moved non-user components to bottom side for aesthetics and space savings.  Fixed the SWD footprint to allow for both SMT and PTH connectors.  Added better docs in schematic.
V3: Added Tag Connect 6-pin connector.  As such, needed to make it a much larger (relatively).
V4: TODO: Some minor updates, no functionality changes.