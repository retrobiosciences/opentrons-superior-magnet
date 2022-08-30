# Opentrons Superior Magnet Module

This repo contains all hardware required to upgrade the stock Opentrons Magnetic Module (side-pellet) with the spring-loaded [Alpaqua 96S Super Magnet](https://www.alpaqua.com/product/96s-super-magnet/) plate. The 96S Super Magnet springload adds z-axis tolerance for pipetting supernatant. Its toroidal pellet is very wide, reducing bead pickup by pipette tip.

<p align="center">
	<img src="https://github.com/retrobiosciences/opentrons-superior-magnet/blob/main/sup_mag.png" alt="superior!" width="500px">
  <p align="center">
    <a href="https://github.com/retrobiosciences/opentrons-pipette-cam">featured: pipette cam </a>
  </p>
</p>

---

Protocols involving SPRIselect and AMPure bead size selection perform poorly with the stock Opentrons Magnetic Module. Pipette positioning is less precise on the OT-2 than other liquid handlers, increasing the difficulty of a proper size selection:
- Ethanol washing directly onto pellet is difficult (inconsistent pellet)
- Tips frequently scrape beads, reducing size selection specificity & yield
- Aspirating supernatant from bottom of well yields inconsistent results:
	- pipette forms seal with bottom of well
	- pipette fails to aspirate all supernatant

### Required hardware:
- [Alpaqua 96S Super Magnet](https://www.alpaqua.com/product/96s-super-magnet/)

### 3d-printed parts:
- magnet plate adaptor:
![magnet plate adaptor](https://github.com/retrobiosciences/opentrons-superior-magnet/blob/main/mag_plate_adaptor.png "")
- microplate riser:
![microplate riser](https://github.com/retrobiosciences/opentrons-superior-magnet/blob/main/microplate_riser.png "")

### How to assemble:
- Remove metal facade from inner side of Magnet Module
- Remove original plate magnet
- Install printed magnet plate adaptor
- Remove & discard blue aluminum Alpaqua baseplate
- Install spring-loaded magnet plate on magnet plate adaptor
- Install microplate riser above magnet plate
