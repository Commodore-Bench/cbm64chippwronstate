# Commodore 64 Chip Troubleshooter Diagram

A diagram of the major and minor chips in the Commodore 64 showing pin state after the machine is first powered on. Intended as an aid to repair and restoration.

Each of the chips is shown with their pins showing a HIGH, LOW, or PULSE tag depending on what state it should be in after
initally powering on the machine. Using a scope, or logic probe you can go through the chips and test the pins without having
to remove the chip from the motherboard.

## How To Use It

First, disconnect any peripherals and remove any cartridges from the expansion port. Then power on the machine.
And grab the probes to your scope, or logic probe. 

The general approach to fault diagnosis is as follows:

- If a chip's inputs match the diagram and the outputs match the diagram then the chip is *probably* good.
- If a chip's inputs match the diagram and the outputs are wrong, then the chip is almost certainly bad.
- If a chip's inputs do not match the diagram, then the problem is caused by a connecting circuit.

Appologies for the rough and ready nature of the diagram. I needed something in a hurry. This is very much a work in progress. I'll
get around to clean up and diagramming the missing chips when I have some time. At the moment, the DRAM chips are not documented and
neither are the CIA chips, other than having pinouts.
