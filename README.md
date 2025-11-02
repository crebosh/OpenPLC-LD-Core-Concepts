# OpenPLC-LD-Core-Concepts
Quick Projects to get some core LD concepts figured out in OpenPLC

## Project 1 Latch
**Main Goals**:
- demo latching
- use OpenPLC to separate variables, control logic, outputs

I want my hardware outputs to live in their own program so that they are easier to monitor. When I jump into HMI it will be easier to manage when it is in it's own program. At least I hope.


## Project 2 Timers
**Main Goals**:
- Timers (TON)
- Use OpenPLC Function Blocks

Moving complicated state controls and sequences to function blocks should make my programs easier to read. By moving my light timers inside the sequencer FB I can shorted the logic needed for the light outputs.
