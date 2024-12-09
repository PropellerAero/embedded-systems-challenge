# Propeller Embedded Systems Challenge

This is a small design task similar to the problems tackled by the Propeller hardware team. We want to see how you approach open ended problems and what you learn along the way. We are more interested in your process and critical thinking than the final result. If there is any ambiguity, make a note of any assumptions made and questions you would ask to resolve them.

## Background

Propeller Aero has recently decided to get into the consumer smart home devices market. Why? We have no idea, but it seemed like a good idea at the time. We've just finished designing the first product in this range, the Propeller LampMate™ and are eager to start manufacturing.

The LampMate is a small table lamp, it features:

- USB-C Power input
- WiFi control
- A warm white LED
- Not much else!

## The task

In this repository you will find the following design files for the LampMate main circuit board:

- `PropellerLampMate/` - The KiCAD EDA design project
- `PropellerLampMate.pdf` - The schematic drawing
- `PropellerLampMate_gerber` - The PCB design in Gerber format
- `PropellerLampMate.png`- A 3D rendering of the layout

### Part A

This design has 10 intential errors in the schematic drawing and 8 in the PCB layout. Find as many as you can and write a couple of sentences for each explaining the problem, what impact it will have and how it should be fixed. Document these issues in whatever format you prefer (document, slide deck, marked up drawings) - focus on being as clear and succinct as possible.

### Part B

When we begin manufacturing the LampMate, the production team will need a programming and test procedure for this PCB. Device firmware will need to be loaded on to the microcontroller and the assembled PCB will need to be tested to ensure there are no assembly errors and it functions as expected.

Draw up a high-level design for a test including:

- A block diagram of any test fixture hardware required
- A process flow digram including the automated and manual steps to take freshly assembled PCBs in and output programmed and tested boards ready for final assembly
- Brief notes on each component and step

Consider in your design:

- Where will test points be required on the LampMate PCB to facilitate programming and testing?
- Which steps can be automated and which must be performed manually by an operator?
- How can we ensure the device functions as expected when the customer receives it?
- What kinds of assembly errors are likely? How can we catch these?
- How can we make this process as simple and fast as possible to minimise cost?
