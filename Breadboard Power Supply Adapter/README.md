# Breadboard Power Supply Adapter

## Background
I've run into some recurring issues when using bench power supplies with projects under development.  
1. The cables tend to be heavy relative to the project PCB.  
2. I commonly use power supplies that are 4-wire, such as the Keithley 2302.
3. The connections will regularly be pushed into a breadboard, and usually in a sloppy manner.

## Solution
A simple board that breaks out the connections into convenient points.  It will get "anchored" by a breadboard, and provide easy connections.

## Change History

| Version | Status | Notes |
| ------- | ------ | ----- |
| V1      | Built and using.  | First attempt at it.  Lessons learned |
| V2      | Ordered | Removed redundant TPs, added Regulator location |

## Lessons learned

1. 0.8mm Thick board is too flexible for this use.
1. Banana Jack connection points can and should be re-used for Wire connections, and possible Keystone hooks.  
1. Add a 3-pin (In, Gnd, Out) option for a regulator or reference.  
