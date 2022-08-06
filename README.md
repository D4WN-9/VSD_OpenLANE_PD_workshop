# An insight into Advanced Physical Design

This repository contains my theoretical and practical comprehension of physical design of semiconductor based chips using open source tools. This work is done under the [Advanced Physical Design Using OpenLANE / SKY130](https://www.vlsisystemdesign.com/advanced-physical-design-using-openlane-sky130/) workshop. This repository also functions as a tutorial for those interested in open source physical design.

## Significance

The main focus is towards the RTL to GDS flow, wherein RTL (a high level description of the required design) is converted all the way to GDSII (complete physical structure description at 130 nanometer level) format. This includes both front-end and back-end VLSI domains. Ultimately, the GDS files are used in the foundry for the design to undergo fabrication process. The image below shows how an ASIC goes through various meticulous design processes before the fabrication is even begun. 

<img src="/img/asic-design-flow.png" alt="Alt text" title="Optional title">

## Installation of open source tools
  The following scripts automate the installation of multiple open source tools required for this workshop
  - [VSDFlow](https://github.com/kunalg123/vsdflow) - Contains script to install - Yosys, blifFanout, graywolf, qrouter, magic, netgen, OpenTimer and OpenSTA
  - [OpenLANE Build Scripts](https://github.com/nickson-jose/openlane_build_script) - Contains OpenLANE build tools.
