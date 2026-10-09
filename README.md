# 5v-power-supply
12 V to 5 V regulated power supply designed in LTspice and KiCad, including schematic, PCB layout, simulation, and documentation.

# 12 V to 5 V Regulated Power Supply

## Overview

A linear regulated power supply designed to convert a 12 V DC input into a 5 V DC output. The project uses LTspice for circuit simulation and KiCad for schematic capture and PCB layout.

## Project Goals

* Design a regulated 5 V power supply.
* Simulate circuit behaviour in LTspice.
* Create a schematic and PCB layout in KiCad.
* Document the design process and engineering decisions.

## Design

* **Input:** 12 V DC
* **Output:** 5 V DC nominal
* **Regulator:** LT1086-5.0
* **Output capacitor:** 10 µF
* **Power indicator:** LED with a 1 kΩ series resistor
* **Connections:** 2-pin input and output connectors

## Tools

* LTspice — circuit simulation
* KiCad — schematic capture and PCB design
* GitHub — version control and documentation

## Repository Structure

* `schematic/` — KiCad schematic
* `pcb/` — KiCad PCB layout
* `simulation/` — LTspice simulation file
* `images/` — PCB renders and screenshots

## Validation

The initial LTspice simulation produced approximately 5.003 V at the output under a 1 kΩ load. The PCB layout passed KiCad's design-rule check.

**Note:** Simulation results and PCB design-rule checks do not replace physical testing. Output regulation, thermal performance, and correct operation should be verified before connecting real hardware.

## Future Improvements

* Verify the final circuit against the regulator datasheet.
* Perform further simulation and load testing.
* Fabricate and test the PCB.
* Document measured results and design revisions.
